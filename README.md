# ESP-EYE CameraWebServer with QR CODE Scanner by qrdec.

This CameraWebServer is built in QR CODE Detection and Decord Function by qrdec.  
See [qrdec](https://github.com/torque/qrdec).  

## Usage

$ git clone ....  
copy all files to Platform io project directory or import.  

## edit CameraWebServer.ino

```
const char* ssid = "Your-ssid";
const char* password = "password";
```

## Build and upload to ESP-EYE

## Run
connect to ESP-EYE Serial  
check ip-address  
Browse http://ip-address  

check QR Detection (On Left Navi)  
and set.    
Resoution: QVGA(320x240)  
pixformat: PIXFORMAT_GRAYSCALE  

QR Code decode results apper on ESP-EYE Serial  
payload: https://www.msn.com/  

You can change pixel_format.  
Stopt Stream  
http://camera-webserver-ip/control?var=pixformat&val=3|4  
  
3:PIXFORMAT_GRAYSCALE  
4:PIXFORMAT_JPEG  
  
Strat Stream  


