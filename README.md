# DroidLicious

DroidLicious , a solution for studying the behavior of Android apps and classifying them accordingly. DroidLicious leverages state-of-the-art static analysis techniques to examine the behavior of Android applications.  DroidLicious also utilizes reliable machine learning methods to detect data-flow patterns in malware and compares them to the patterns of data-flows exist in benign apps.<br/>
<br/>
Please check out website: https://DroidLicious.cc/<br/>

### Controller:
-command <br/>
befor you run it ,change line 12 in startFlowDroid.py <br/>

-------------------------------<br/>
python main.py "Apk/txt path" <br/>
-------------------------------<br/>
python main.py --fd_option "options" "Apk path"

### Dataset:
Parser has two forms, first form:<br/>
-------------------------------<br/>
|Name | Source| Sink | label  |<br/>
-------------------------------<br/>


- Another form is: <br/>
-------------------------------<br/>
|Name | Src n ~> Snk n | label|<br/>
-------------------------------<br/>


