In the time of a pandemic, it is important to keep a minimum distance from others to prevent
the spread of disease. However, it is not easy to measure this distance in real life. To help this
issue, we aim to build a visual assistant to track the own distance from others on the street.

Assuming there is a user with a monocular mobile phone camera, webcam, or video we detect humans, estimate their depths from RGB image and build a warning
mechanism.

**This project was built within [Perception and Learning in Robotics and Augmented Reality](http://campar.in.tum.de/Chair/TeachingSS20PLARR) praktikum offered at the Technical University of Munich (TUM) in summer semester 2020.**

## Sample Video<sup>[1]</sup>

![Sample](/sample.gif)

## Pipeline

![Pipeline](/pipeline.png)

## Application

- Mobile application: [https://github.com/plarr2020-team1/flutter_app](https://github.com/plarr2020-team1/flutter_app)
- Video or webcam application: [https://github.com/plarr2020-team1/application](https://github.com/plarr2020-team1/application)

#### Monocular depth estimation

- Monodepth2<sup>[2]</sup>
- Mannequin Challenge<sup>[3]</sup>

#### Human segmentation / tracking
- YOLACT<sup>[4]</sup>
- Tracktor<sup>[5]</sup>

and more! Make sure to checkout our Github org: [https://github.com/plarr2020-team1](https://github.com/plarr2020-team1)

### Contributers

Built by
- Enis Simsar [(enisimsar)](https://github.com/enisimsar)
- Ehsan Shafiei [(aestuans)](https://github.com/aestuans)
- Dilara Gökay [(dilaragokay)](https://github.com/dilaragokay)

Supervised by Evin Pınar Örnek [(evinpinar)](https://github.com/evinpinar)

### References
[1] 	Leal-Taixé, Laura, et al. "Motchallenge 2015: Towards a benchmark for multi-target tracking." _arXiv preprint arXiv:1504.01942_ (2015).   
[2]   Godard, Clément, et al. "Digging into self-supervised monocular depth estimation." _Proceedings of the IEEE international conference on computer vision_. 2019.   
[3]   Li, Zhengqi, et al. "Learning the depths of moving people by watching frozen people." _Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition_. 2019.   
[4]   Bolya, Daniel, et al. "Yolact: Real-time instance segmentation." _Proceedings of the IEEE international conference on computer vision_. 2019.   
[5]   Bergmann, Philipp, Tim Meinhardt, and Laura Leal-Taixe. "Tracking without bells and whistles." _Proceedings of the IEEE international conference on computer vision._ 2019.
