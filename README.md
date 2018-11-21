# QwaveOpenCV

OpenCV wrapper functions for LabVIEW for Raspberry Pi 3B/3B+/3A+.

[**QwaveOpenCV**](https://github.com/QWaveSystems/QwaveOpenCV-Examples) is a additional functions for image processing or machine vision application using OpenCV functions. 

**QwaveOpenCV** package is required [**QwaveCameraCV**](https://github.com/QWaveSystems/QwaveCameraCV) to communicate with camera under Raspberry Pi (ARMv7 Linux enviromnent).

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-06.png)

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-09.png)

**Installation**

1.Download and Install **"qwave_opencv_raspberrypi-xx.xx.vip"** using VIPM (VI Package Manager).

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-08.png)

2.After installed you can find functions under **Vision and Motion > QwaveOpenCV** palette.

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-00.png)

3.The example project is located at **"C:\Program Files (x86)\National Instruments\LabVIEW 2014\examples\QwaveOpenCV"**. Open **"QwaveOpenCV-Examples.lvproj"**

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-04.png)

4.Run the **"Canny Function OpenCV.vi"**

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-05.png)

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-06.png)

5.Run the **"Play Video MP4 AVI.vi"**

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-07.png)

6.The source code for OpenCV function and template are located at [**QwaveCV**](https://github.com/QWaveSystems/QwaveCV) repository.

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-01.png)

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-02.png)

![](http://ftp.qwavesys.com/tmp_pics/QwaveOpenCV-03.png)

7.Steps to build library *.so from source (C/C++) refer to QwaveCV repo.

[https://github.com/QWaveSystems/QwaveCV](https://github.com/QWaveSystems/QwaveCV)

1.sudo schroot -r -c lv

2.git clone https://github.com/QWaveSystems/QwaveCV.git

3.cd QwaveCV

4.mkdir build

5.cd build

6.cmake ..

7.make

8.make install

8.There is addtion examples, Download and Install **"qwave_opencv_examples-xx.xx.vip"** using VIPM (VI Package Manager).

![](http://ftp.qwavesys.com/tmp_pics/OpenCV_Examples-01.png)

9.The example project is located at **"C:\Program Files (x86)\National Instruments\LabVIEW 2014\vi.lib\Q-Wave Systems\QwaveOpenCV_Examples"**. Open **"Qwave Vision Example.lvproj"**

![](http://ftp.qwavesys.com/tmp_pics/OpenCV_Examples-02.png)

![](http://ftp.qwavesys.com/tmp_pics/OpenCV_Examples-03.png)
-----------------------------------------------------------------

-Raspberry Pi™ is a registered trademark of the Raspberry Pi foundation.

-OpenCV is released under a BSD license and hence it’s free for both academic and commercial use. `(http://opencv.org/)`

------------------------------------------------------------------
Created by `Amornthep Phunsin` and `Supawat Armart` (Q-Wave Systems)
Contact : `"amornthep@qwavesys.com"`
