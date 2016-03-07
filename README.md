# ESP8266_RTOS_SDK #

----------

ESP8266 SDK based on FreeRTOS.
   
## Note ##

More details in "Wiki" !

## Requrements ##

You can use both xcc and gcc to compile your project, gcc is recommended.
For gcc, please refer to [esp-open-sdk](https://github.com/pfalcon/esp-open-sdk).

  
## Compile ##

Clone ESP8266_RTOS_SDK, e.g., to ~/ESP8266_RTOS_SDK.

    $git clone https://github.com/espressif/ESP8266_RTOS_SDK.git

Modify gen_misc.sh or gen_misc.bat:
For Linux:

    $export SDK_PATH=~/ESP8266_RTOS_SDK
    $export BIN_PATH=~/ESP8266_BIN

For Windows:

    set SDK_PATH=/c/ESP8266_RTOS_SDK
    set BIN_PATH=/c/ESP8266_BIN

ESP8266_RTOS_SDK/examples/project_template is a project template, you can copy this to anywhere, e.g., to ~/workspace/project_template.

Generate bin: 
For Linux:

    ./gen_misc.sh

For Windows:

    gen_misc.bat
   
Just follow the tips and steps.

## Download ##

* Using [ESP Flash Download Tool](http://bbs.espressif.com/viewtopic.php?f=57&t=433) and select the right flash size on the tool while downloading.  
  
* Flash Map & Download Address refer to documentation [2A-ESP8266-SDK__Getting_Started_Guide](http://bbs.espressif.com/viewtopic.php?f=51&t=1024).   
