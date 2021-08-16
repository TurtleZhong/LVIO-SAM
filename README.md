# LVIO-SAM
A multi-sensor fusion odometry, LVIO-SAM, which fuses LiDAR, stereo camera and inertial measurement unit (IMU) via smoothing and mapping.

- The code is still being integrated. we will release it in the feature.


# LVIO-SAM

A multi-sensor fusion odometry, LVIO-SAM, which fuses LiDAR, stereo camera and inertial measurement unit (IMU) via smoothing and mapping.


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/TurtleZhong/LVIO-SAM">
    <img src="images/lvio-sam-kitti.gif" alt="Logo" width="80%">
  </a>
  <a href="https://github.com/TurtleZhong/LVIO-SAM">
    <img src="images/lvio-sam-cmu.gif" alt="Logo" width="80%">
  </a>

  <h3 align="center">LVIO-SAM</h3>

  <p align="center">
    A multi-sensor fusion odometry, LVIO-SAM, which fuses LiDAR, stereo camera and inertial measurement unit (IMU) via smoothing and mapping.
    <!-- A basic implementation of <a href="https://arxiv.org/abs/2007.01813">AVP-SLAM: Semantic Visual Mapping and Localization for Autonomous Vehicles in the Parking Lot(IROS 2020)</a> in simulation! -->
    <br />
    <a href="https://www.youtube.com/playlist?list=PLBBuFHQF08z4xjS1IwlQQE0rfKYv4aBD1">Demo Youtube</a>
    ·
    <a href="https://www.bilibili.com/video/BV1Hq4y1S7aL?share_source=copy_web">Demo Bilibili</a>
    ·
    <a href="https://github.com/TurtleZhong/LVIO-SAM/issues">Report Bug</a>
    ·
    <a href="https://github.com/TurtleZhong/LVIO-SAM">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#simulations environment">Simulations environment</a></li>
    <li><a href="#how to run">How to run</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
### About The Project
&emsp;&emsp; This project is provide a a multi-sensor fusion odometry, LVIO-SAM, which fuses LiDAR,stereo camera and inertial measurement unit (IMU) via smoothing and mapping.

`!!!Important Notes!!!`



### Simulations environment
&emsp;&emsp; We modify the Gazebo world proposed in [here](https://github.com/jizhang-cmu/ground_based_autonomy_basic) and adding our own sensors to test our proposed method. We use [Husky](https://github.com/husky/husky) as the base robot and we modify the urdf. The robot is equiped with A velodyne VLP 16 lidar, stereo camera(640x480) and an IMU (50Hz).

Download the [CMU campus model](https://drive.google.com/file/d/1GGZsf5QYhy6wGUXvzUn1D8RzcYzM_O4f/view?usp=sharing) to `sim_env/husky_gazebo/mesh/`
```bash
cd YOUR_WORD_PATH/LVIO_SAM/sim_env/husky_gazebo/mesh/
unzip autonomus_exploration_environments.zip
```

I guess c `campus` model it to `~/.gazebo/models/`.
```bash
cd autonomus_exploration_environments/
cp -r campus ~/.gazebo/models/
```

you can launch gazebo and find campu model just like this.

<p align="center">
  <a href="">
    <img src="images/.png" alt="[Logo]" width="90%">
  </a>
</p>


### How to run

&emsp;&emsp; Since our code is still being integrated. we will release it in the feature. But we provide a docker environment for users.  So [Docker]() should be correctly installed.

```bash
docker pull ***

```

```bash
cd LVIO-SAM/

```

```bash

```


&emsp;&emsp; 
```bash

```


If everything is OK, you will get this:
<p align="center">
  <a href="">
    <img src="images/model_to_gazebo.gif" alt="[Logo]" width="90%">
  </a>
</p>



<!-- ROADMAP -->
### Roadmap

* [Gazebo]()
* [simulation environment]()
* [lidar visual inertial odometry]()
* [......]()



<!-- CONTRIBUTING -->
### Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
### License

Distributed under the MIT License.


<!-- CONTACT -->
### Contact

Xinliang Zhong - [@zxl](null) - xinliangzhong@foxmail.com


Project Link: [https://github.com/TurtleZhong/LVIO-SAM](https://github.com/TurtleZhong/LVIO-SAM)



<!-- ACKNOWLEDGEMENTS -->
### Acknowledgements
* [ROS](http://wiki.ros.org/)
* [Gazebo](http://gazebosim.org/)
* [LOAM]()
* [LIO-SAM]
* [VINS-FUSION]
* [LVI-SAM]



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/TurtleZhong/LVIO-SAM.svg?style=for-the-badge
[contributors-url]: https://github.com/TurtleZhong/LVIO-SAM/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/TurtleZhong/LVIO-SAM.svg?style=for-the-badge
[forks-url]: https://github.com/TurtleZhong/LVIO-SAM/network/members
[stars-shield]: https://img.shields.io/github/stars/TurtleZhong/LVIO-SAM.svg?style=for-the-badge
[stars-url]: https://github.com/TurtleZhong/LVIO-SAM/stargazers
[issues-shield]: https://img.shields.io/github/issues/TurtleZhong/LVIO-SAM.svg?style=for-the-badge
[issues-url]: https://github.com/TurtleZhong/LVIO-SAM/issues
[license-shield]: https://img.shields.io/github/license/TurtleZhong/LVIO-SAM.svg?style=for-the-badge
[license-url]: https://github.com/TurtleZhong/LVIO-SAM/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/TurtleZhong


