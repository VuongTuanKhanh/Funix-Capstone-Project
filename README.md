<div align="center">
<p>
<img width="850" src="images/splash.jpg">
</p>
<br>
<div>
<a href="./tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
<a href="./tutorial.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a>
<a href="#"><img src="https://img.shields.io/docker/pulls/ultralytics/yolov5?logo=docker" alt="Docker Pulls"></a>
</div>

  <br>
  <div align="center">
    <a href="https://github.com/VuongTuanKhanh">
        <img src="./images/logo-social-github.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://www.linkedin.com/in/vuong-tuan-khanh/">
        <img src="./images/logo-social-linkedin.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://twitter.com/">
        <img src="./images/logo-social-twitter.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://youtube.com/">
        <img src="./images/logo-social-youtube.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://www.facebook.com/vuongtuankhanh99">
        <img src="./images/logo-social-facebook.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://www.instagram.com/archius_vuong//">
        <img src="./images/logo-social-instagram.png" width="2%"/>
    </a>
</div>

<br>
<p>
<a href="https://github.com/VuongTuanKhanh/Funix-Capstone-Project"><b>Object Detection project</b></a> 🚀 is the capstone project on object recognition through images and videos, inspired by the <a href="https://www.aicrowd.com/challenges/airborne-object-tracking-challenge">Airborne Object Tracking Challenge</a>
<br>
This project mainly works with <b>AOT</b> dataset, with a volume of up to 13TB, ambitious towards researching various algorithms such as <a href ="https://pjreddie.com/darknet/yolo/">YOLOv3</a>, <a href ="https://arxiv.org/abs/2004.10934">YOLOv4</a>, <a href ="https://github.com/ultralytics/yolov5">YOLOv5</a>, as well as <a href ="https://github.com/amazon-research/siam-mot">SiamMOT</a>. In addition to studying the paper and applying theory to practice, the project also aims to build custom libraries and deploy the project in practice.
</p>

## <div align="center">About the Challenge</div>
<div align="left">

One of the important challenges of autonomous flight is the **Sense and Avoid (SAA)** task to maintain enough separation from obstacles. While the route of an autonomous drone might be carefully planned ahead of its mission, and the airspace is relatively sparse, there is still a chance that the drone will encounter unforeseen airborne objects or static obstacles during its autonomous flight.

The autonomous **SAA** module has to take on the tasks of situational awareness, decision making, and flying the aircraft, while performing an evasive maneuver.

There are several alternatives for onboard sensing including radar, LIDAR, passive electro-optical sensors, and passive acoustic sensors. Solving the **SAA** task with visual cameras is attractive because cameras have relatively low weight and low cost.

**For the purpose of this project, I consider a  solution that solely relies on a single visual camera and Computer Vision technique that analyzes a monocular video.**

Flying airborne objects pose unique challenges compared to static obstacles. In addition to the typical small size, it is not sufficient to merely detect and localize those objects in the scene, because prediction of the future motion is essential to correctly estimate if the encounter requires a collision avoidance maneuver and create a safer route. Such prediction will typically rely on analysis of the motion over a period of time, and therefore requires association of the detected objects across the video frames.

**As a preliminary stage for determining if a collision avoidance maneuver is necessary**, this challenge will be concerned with spatio - temporal airborne object detection and tracking, given a new **Airborne Object Tracking** dataset, and perform two benchmarks:

<ul align="left">
  <li>Airborne detection and tracking</li>
  <li>Frame-level airborne detection</li>
</ul>
</div>

<img src="./images/challenge_description.gif">

## <div align="center">Environments and Integrations</div>


<div align="center">
    <a href="./tutorial.ipynb">
        <img src="./images/logo-colab-small.png" width="15%"/>
    </a>
    <a href="#">
        <img src="./images/logo-kaggle-small.png" width="15%"/>
    </a>
    <a href="#">
        <img src="./images/logo-docker-small.png" width="15%"/>
    </a>
    <a href="#">
        <img src="./images/logo-aws-small.png" width="15%"/>
    </a>
    <a href="https://github.com/VuongTuanKhanh/Funix-Capstone-Project">
        <img src="./images/logo-gcp-small.png" width="15%"/>
    </a>
    <a href="#">
        <img src="./images/logo-wb-small.png" width="15%"/>
    </a>
</div> 

## <div align="center">Contribute</div>

We love your input! We want to make contributing to this project as easy and transparent as possible. Please see
our [Contributing Guide](CONTRIBUTING.md) to get started.

## <div align="center">Contact</div>

For issues running this project please visit [GitHub Issues](https://github.com/VuongTuanKhanh/Funix-Capstone-Project/issues). For business or
professional support requests please visit [https://www.facebook.com/vuongtuankhanh99](https://www.facebook.com/vuongtuankhanh99).

## <div align="center">License</div>

By contributing, you agree that your contributions will be licensed under the <a href="https://opensource.org/licenses/MIT">MIT license</a>

<br>

<div align="center">
    <a href="https://github.com/VuongTuanKhanh">
        <img src="./images/logo-social-github.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://www.linkedin.com/in/vuong-tuan-khanh/">
        <img src="./images/logo-social-linkedin.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://twitter.com/">
        <img src="./images/logo-social-twitter.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://youtube.com/">
        <img src="./images/logo-social-youtube.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://www.facebook.com/vuongtuankhanh99">
        <img src="./images/logo-social-facebook.png" width="2%"/>
    </a>
    <img width="2%" />
    <a href="https://www.instagram.com/archius_vuong//">
        <img src="./images/logo-social-instagram.png" width="2%"/>
    </a>
</div>