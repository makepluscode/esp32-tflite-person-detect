# esp32-tflite-person-detect

Download source code
```
git clone --recurse-submodule https://github.com/makepluscode/esp32-tflite-person-detect.git
```

Build
```
. ~/esp/esp-idf/export.sh
idf.py build
```

Flash
```
idf.py --port /dev/ttyUSB0 flash
```

Monitor
```
idf.py -p /dev/ttyUSB0 monitor
```
