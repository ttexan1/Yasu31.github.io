---
name: Internship at Connected Robotics
summary: Lead developer for the ice cream robot
image: ice-cream.jpg
duration: Feb 2018~
video: <iframe width="560" height="315" src="https://www.youtube.com/embed/0Q0_jMWFcIw?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
---
* [Connected Robotics website](https://connected-robotics.com)
* "Interview" on Wantedly.com in Japanese([1/3](https://www.wantedly.com/companies/connectedrobotics/post_articles/139621), [2/3](https://www.wantedly.com/companies/connectedrobotics/post_articles/140612?source=feed-activities-following), [3/3](https://www.wantedly.com/companies/connectedrobotics/post_articles/141698?source=feed-activities-following))
* [my blog post](/2018/11/02/connected-robotics.html), in Japanese

Connected Robotics is a company in Tokyo that aims to revolutionize cooking through the use of robots. During my internship from February to August, I was assigned to create a new ice-cream serving robot.
I did most of the design and development myself, with assistance from the company. The robot is designed with human interaction in mind- that is why I attached eyeballs that can communicate the intention of the robot to humans, and why it has a bird-shaped design. In its hand is a weight
sensor (load cell), which can measure the weight on the hand. The data from this is used to dynamically adjust the speed of the "curling movement" when it is serving ice cream. This enables the robot to serve about the same amount of ice cream each
time, regardless of the flow rate.
 It is written mostly in Python, and uses ROS for internal communication and frame transform calculation(used to calculate joint angles for eyes).
