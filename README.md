### Devices
- Desktop (passmark 2584, 95W) https://www.cpubenchmark.net/cpu.php?cpu=Intel+Core+i7-7700K+%40+4.20GHz&id=2874
- X200 (passmark 905, 17W) https://www.cpubenchmark.net/cpu.php?cpu=Intel+Pentium+2117U+%40+1.80GHz&id=1872
- Jetson TX2 (-, 7.5W) https://www.phoronix.com/scan.php?page=article&item=march-2017-arm&num=2
- Euclid (passmark 552, 4W) https://www.cpubenchmark.net/cpu.php?cpu=Intel+Atom+x7-Z8700+%40+1.60GHz&id=2506

### Benchmark
- EuRoC Mono & Stereo https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets
- TUM VI Mono & Stereo https://vision.in.tum.de/data/datasets/visual-inertial-dataset
- TUM RGBD Mono https://vision.in.tum.de/data/datasets/rgbd-dataset
- ICL NUIM Mono https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html
- KITTI Stereo http://www.cvlibs.net/datasets/kitti/eval_odometry.php

### VO/VSLAM/VINS Systems Assessed
- Proposed Good Feature Mono https://github.com/YipuZhao/GF_ORB_SLAM
- Proposed Good Feature Stereo [will be release soon]
- ORB-SLAM Mono https://github.com/YipuZhao/ORB_SLAM
- ORB-SLAM Stereo https://github.com/YipuZhao/ORB_SLAM2
- SVO Mono & Stereo https://github.com/YipuZhao/rpg_svo
- DSO Mono https://github.com/YipuZhao/DSO
- ROVIO Mono https://github.com/YipuZhao/rovio
- VINS-Mono https://github.com/YipuZhao/VINS-Mono
- MSCKF Stereo https://github.com/YipuZhao/msckf_vio
- OKVIS Stereo https://github.com/YipuZhao/okvis

Compared to the official repos, the baseline methods in my repo are with explicit logging on pose tracking and time cost.
