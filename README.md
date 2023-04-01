# PYINSTALLER

Installing py installer

pip install pyinstaller
pip3 install pyinstaller


creating one file exe with pip packages

pyinstaller --noconsole --onefile
--paths="C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\mss;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\base64;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\os;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\requests;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\time;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\datetime;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\threading;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\wmi;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\socket;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\pythoncom;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\browser_history;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\psutil;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\subprocess;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\win32process;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\win32gui;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\pynput;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\logging;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\win32com;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\ctypes;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\json;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\csv;C:\Users\<username>\AppData\Local\Programs\Python\Python310\Lib\site-packages\winapps"
moniter.py


Creating normal installer

pyinstaller main.py

In linux

pyinstaller -D -F -n main -c "main.py"



