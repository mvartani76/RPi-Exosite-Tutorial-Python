RPi-Exosite-Tutorial-Python
===========================

Simple hello world example in python demonstrating use of exosite portal

http://support.exosite.com/hc/en-us/articles/200094608-Hello-World-app-in-Python-

https://github.com/exosite-garage/python_helloworld

========================================
About
========================================
python_helloworld.py is a simple python script that demonstrates how to send data to
the Exosite over HTTP.<br>
License is BSD, Copyright 2011, Exosite LLC<br>
Built/tested with Python 2.6.5 Also tested with Python 2.7<br> 

========================================
Quick Start
========================================
****************************************
<b>1) install python</b>
****************************************
http://www.python.org/download/<br>
http://www.python.org/download/releases/2.6.5/<br>
http://www.python.org/ftp/python/2.6.5/python-2.6.5.msi<br>
<br>
Verified that it works with Python2.7 but not Python3.2<br>

****************************************
<b>2) test it out</b>
****************************************
edit python script "python_helloworld.py"<br> 
--) update the default device CIK -> Get your CIK (KEY) from your Portals account<br>
--) add two data sources to your device in your portals account<br>
-----) Data Source 1 should be named 'Message', type is string, alias is 'message'<br>
-----) Data Source 2 should be named 'Number', type is integer, alias is 'number'<br>
       NOTE: It is important to provide the alias when creating these data sources, the script will not work without doing this correctly.<br>
--) run the script (> python python_helloworld.py)<br>
--) verify the app connects, sends data (no errors should be generated, should see 204 Response), and reads the data back (number = 1, message = hello world!)<br>
--) log into exosite.com and verify the data sources were updated<br>

****************************************
<b>3) tweak it</b>
****************************************
--) add a 'print' command or something <br>
--) play around, use it, extend it!<br>
