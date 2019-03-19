# Tensorflow for raspberry pi and Odroid

#### There are compiled bineries of tensorflow for all raspberry pi  versions

#### all binaries was compiled in debian stretch
``` By ```

| [Safdar Khan](https://www.safdarkhan.cf) |
| ---------------------------------------- |

___________________________
**Directory Structures**
```
Tensorflow-x version
|-- Raspberry pi one/zero with openblas
    |-- tensorflow-x-cp27-none-linux_armv6l.whl
    |-- tensorflow-x-cp35-none-linux_armv6l.whl
|-- Raspberry pi 2/3
    |-- tensorflow-x-cp27-none-linux_armv7l.whl
    |-- tensorflow-x-cp35-none-linux_armv7l.whl
|-- Odroid-c2
    |-- tensorflow-x-cp27-none-linux_aarch64.whl
    |-- tensorflow-x-cp35-none-linux_aarch64.whl
```

_____________________
# How to use them
1. simply click on whl file click on `Raw` and get download link of whl file
2. open terminal of rasberian or Odroid
3. use pip to install that whl file as
```python3 -m pip install whllink```
*Note that*
* Replace python3 by your desired python version and whllink with your download whl link
* go to the path where you download the file with the extention *.whl
* whl install by 
```pip install package.whl```
that works if you have downloaded whl file for further wheel installetion follow this [link](https://pythonwheels.com/) 

### verify Tensorflow
```$python3```
```
>>import tensorflow as tf
>>tf.__version__
```
```1.13.1```
- if that gave a output like this it means that tensorflow is installed properly

