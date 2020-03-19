# MOIL Development Workflow

There are 2 libraries for MOIL development. Moildev is based on OpenCV and has been tested 
both on Ubuntu 18.04 over x86/x64 and Raspbian over Raspberry Pi. Qt_Moildev is based on OpenCV and Qt, it has been tested on Ubuntu 18.04 over x86/x64.

If you pay attention on the performance or running your application on Raspberry Pi, please use Moildev. Or, if you need more complex UI design, please use Qt_Moildev. The followings listed the related items. 


## 1. Moildev

Moildev is a static MOIL library, support both x86/x64 and Raspberry Pi. The corresponding example project is Mainmoil_6view. The output library .a file from Moildev is depend on the development platform, that is, moildev.a for x86/x64 and moildev_rpi.a for Raspberry Pi.      
Repositories : 

A. Moildev ( PRIVATE)

<https://github.com/cjchng/moildev>
    
B. Moil_SDK ( PUBLIC )

<https://github.com/cjchng/moil_sdk>

C. Mainmoil_6View ( Public )

<https://github.com/cjchng/mainmoil_6view>



![P1](https://user-images.githubusercontent.com/12620285/77124299-71beb000-6a7d-11ea-8179-4a357761093f.png)




## 2. Qt_Moildev 

Qt_Moildev is a shared library(.so) for Qt development environment. The generated library
must be installed in the development environment. Please see the instructions in 
the repositories. 

A. Qt_Moildev ( PRIVATE )

<https://github.com/cjchng/qt_moildev> 

B. Qt_Mainmoil ( PRIVATE ), include the required .so library and install script.

<https://github.com/yourskc/qt_mainmoil>


![P2](https://user-images.githubusercontent.com/12620285/77124357-9ca90400-6a7d-11ea-8f3c-bf5f44997eee.png)



