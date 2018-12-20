Real-time 'Actor-Critic' tracking using drawn box
=========================================

Introduction
--------------------------------
We modify the ACT to use the drawn box for driving the network

Requirements
--------------------------
1. Tensorflow 1.4.0 (Train) and Pytorch 0.3.0 (Test)
2. CUDA 8.0 and cuDNN 6.0
3. Python 2.7

Usage
--------------------------
### Train
  1. Please download the `ILSVRC VID dataset`, and put the `VID` folder into `$(ACT_root)/train/` </br>
  (We adopt the same videos as [meta_trackers](https://github.com/silverbottlep/meta_trackers). You can find more details in `ilsvrc_train.json`.)
  2. Run the `$(ACT_root)/train/DDPG_train.py` to train the 'Actor and Critic' network.
### Test
  Please run `$(ACT_root)/tracking/run_tracker.py` for demo.
 
Citation
--------------------
If you find ACT useful in your research, please kindly cite our paper:

--------------------
If you have any questions, please feel free to contact liulj13@qq.com

Acknowledgments
------------------------------
Many parts of this code are adopted from other related works

