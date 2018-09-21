---
name: Mini Walker Project
summary: small leg robot that kind of walks
image: walker.JPG
duration: Feb. 2018 ~ Apr. 2018
video: <iframe width="560" height="315" src="https://www.youtube.com/embed/tQKB5TPjc7M?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
---
* [GitHub repo](https://github.com/Yasu31/walker)

Watching the video <a href="https://www.youtube.com/watch?v=-Vg-BdXps50">人間のような自然な歩き方をするロボット(Biped robot walks just like a human being.)</a> inspired me to create one of my own walking mini robot. I decided to first read up on past research about bipedal walking algorithms, and found **countless** walking gaits. They range from simple (interpolating between known statically stable poses to create motion) to I-have-no-idea-how-it-works complex([sing convex optimization to plan dynamic motion trajectories for the Atlas robot](https://www.google.co.jp/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwiElp2Tl6PaAhUIi7wKHZKKAkIQFggoMAA&url=https%3A%2F%2Fdspace.mit.edu%2Fopenaccess-disseminate%2F1721.1%2F110533&usg=AOvVaw1gKi1wb1qCIAaVTiVZqGG-)).

Here, I implemented a gait based on the LIPM(Linear Inverted Pendulum Mode). It's very lightly described in the video, but please refer to the original paper if you're interested.

<ul>
    <li>
      Kajita, Shuuji & Kanehiro, Fumio & KANEKO, Kenji & Yokoi, Kazuhito & Hirukawa, Hirohisa. (2001). <a href="https://pdfs.semanticscholar.org/6a31/6e0d44e35a55c41a442b3f0d0eb1f9d4d0ca.pdf">The 3D linear inverted pendulum model: A simple modeling for a biped walking pattern generation.</a>      1. 239 - 246 vol.1. 10.1109/IROS.2001.973365. </li>
    <li>
      Garton H., Bugmann G., Culverhouse P., Roberts S., Simpson C., Santana A. (2014) <a href="https://www.google.co.jp/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=0ahUKEwjP87LBlqPaAhWMf7wKHfi_BfcQFgg1MAI&url=https%3A%2F%2Fwww.researchgate.net%2Fprofile%2FMohamed_Mourad_Lafifi%2Fpost%2FHow_can_I_calculate_the_walking_speed_of_humanoid_robot%2Fattachment%2F59d6506679197b80779a9416%2FAS%253A502748711002112%25401496876041457%2Fdownload%2FHumanoid%2BRobot%2BGait%2BGenerator%2B_%2BFoot%2BSteps%2BCalculation%2Bfor%2BTrajectory%2BFollowing.pdf&usg=AOvVaw1HoDCOiyM8XaVbk_n6lpv7">Humanoid Robot Gait Generator: Foot Steps Calculation for Trajectory Following.</a>      In: Mistry M., Leonardis A., Witkowski M., Melhuish C. (eds) Advances in Autonomous Robotics Systems. TAROS 2014. Lecture Notes in Computer Science, vol 8717. Springer, Cham
    </li>
  </ul>
