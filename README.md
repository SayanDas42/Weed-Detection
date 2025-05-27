# Weed-Detection
This project detects weeds from plants in an agricultural field.
In this Guide we have included different installation scenarios based on your experience in executing the program. 
Please note that some of these may not be relevant to your installation plan.

1. As this is a python program, at first install the Python IDLE. 
    Browse to http://www.python.org/download
    Look for the Windows downloads, choose the one appropriate for your architecture (32-bit or 64-bit). 
At the time of writing, the choices are:
        32-bit: Python 2.7.3 Windows Installer
        64-bit: Python 2.7.3 Windows X86-64 Installer
    If you don't know the system architecture, try running winmsd.exe (in Windows XP) or msinfo32.exe (in Windows 7). Look at System Type and/or Processor. It will look this this for 32-bit, or this  	for 64.
    Run the installer and click through the prompts. Default options are usually just fine. This installs IDLE, too, by default.

While installing Python tick the Environment Variable Box.

2. Install Numpy through Command Prompt using the command – pip install numpy

3. Install Six module through Command Prompt using the command – pip install six

4.  Install Tensorflow through Command Prompt using the command –
pip install –upgrade tensorflow.
      With pip, you can install TensorFlow with GPU support as follows: pip install tensorflow-gpu
(NOTE : It is recommended to install Tenserflow version 1.14. You can do that with the following command – python -m pip instal tensorflow==1.14. In Tensorflow version 2 all object detection notebooks and models have not been verified.)
	

5. Install matplotlib through Command Prompt using the command – pip install matplotlib

6. Install pillow through Command Prompt using the command – pip install –upgrade Pillow.

7. Object Detection(Move the object_detection to the “site package” of the installed python language i.e. C:\Users\user\AppData\Local\Programs\Python\Python37\Lib\site-packages).

8. Install opencv-python through Command Prompt using the command – pip install opencv-python.

9. Install Visual C++ if you encounter some missing dll files from here.

10. Finally go inside 'object_detection' folder and run'model_main.py'.

Please make sure you have all of the above modules and Python installed before you proceed to execute the program.

Thank you.
