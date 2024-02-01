## Camera testing scripts for Raspberry Pi

These files are mainly to test that OpenCV and the Raspberry Pi Camera are installed and working.

Make sure to install OpenCV (cv2) for Python first. 

Test if you have cv2 already. It should not give an error when opening a Python Script and importing cv2
```bash
  $ python3
   >>> import cv2

```
If you need to install it:
```bash
   $ sudo apt update
   $ sudo pip install opencv-python
```
If you need to upgrade numpy (because it complained) first run:
```bash
  $ pip install --upgrade numpy
```

Running these tests will confirm you have both CV2 and a camera connected and working.
