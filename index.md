# windows_pycharm_tensorflow
How to create the environment for using tensorflow-GPU in Windows?

In total, you need to download Nvidia Driver + Pycharm + Anaconda + tensorflow-gpu + CUDA + cuDNN. Please note that a corresponding version of tensorflow can only be used with the corresponding Anaconda, CUDA and cuDNN. What I used is Anaconda3-5.2.0 (python 3.6.5) + CUDA 10.1 + cuDNN 7.6.3 + tensorflow 1.12.0. The latest version of tensorflow can also be used.

1. Check your GPU capability and download the correponding Nvidia driver for your GPU (https://www.nvidia.com/Download/index.aspx).

2. (Optional) Download Pycharm IDE (https://www.jetbrains.com/pycharm/download/#section=windows).

3. Download Anaconda (https://www.anaconda.com/). Please download a suitable version of it.

4. Download and install CUDA (https://developer.nvidia.com/accelerated-computing-toolkit).

5. Download cuDNN (https://developer.nvidia.com/rdp/form/cudnn-download-survey). 
Unzip the files you have downloaded and then copy them to the corresponding CUDA file folders. 
You may have three different file folders in cuDNN which are "bin", "include" and "lib". 
Copy the files to "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\bin", "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\include" and "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\lib\x64" respectively.
