## 10 steps to ensure a proper Python installation.

1. [The Python homepage](https://www.python.org/downloads/ "Python Homepage")

2. Download the latest version for Windows.

3. Follow the steps for default installation.

You have now successfully installed Python for Windows 10. With this installation, the IDLE module follows.

Next, Python should be added to your PATH.

4. Open a new IDLE window.

5. Type in the following:
	```python
	import os
	import sys
	os.path.dirname(sys.executable)
	```
 
The output of the execution of this command should give you the path in which Python has been installed.

Example of output:

```C:\\Users\\UNAME\\AppData\\Local\\Programs\\Python\\Python38-32```

We will now use this information to update the path variable.

6. Press the Win-key and search for 'environment', and you should be able to access 'Edit the environment variables'.

7. Press 'Environment Variables..." within the advanced tab of the window.

8. Within the newly opened window, find the 'Path' variable, click it, and click edit.

9. Now, click new, and paste the output from the IDLE command.

10. Open up 'command prompt' and type: 'python', then 'enter'.

If everything has been done correctly, the output should tell you what version of Python you've got installed. If that coincides with the version you installed from python.org, the installation of Python has succeeded.

### Other useful guides
[Anaconda Step-By-Step](https://docs.anaconda.com/anaconda/install/windows/ "Anaconda Installation Guide")