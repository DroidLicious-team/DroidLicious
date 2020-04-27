# DroidLicious

DroidLicious , a solution for studying the behavior of Android apps and classifying them accordingly. DroidLicious leverages state-of-the-art static analysis techniques to examine the behavior of Android applications.  <br/>

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


