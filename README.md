To build for ESP8266 or ESP, go to the corresponding folder src and run either 'make flash' or 'idf.py build' (respectively) in that folder. Do not run these commands in the 'main' of either of these folders. It will error.

Ensure that IDF_PATH and IDF_PATH_ARC are set to their respective SDK's which are in ~/esp.