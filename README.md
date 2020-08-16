[![Code Health](https://landscape.io/github/pyskell/slouchy/master/landscape.svg?style=flat)](https://landscape.io/github/pyskell/slouchy/master)

# slouchy
Slouchy uses your webcam to check if you're slouching and alert you if you are. This project is still in active development and not feature complete.

# Requirements
You need to install the following system-wide:

* Python 3
* [Qt5](https://doc.qt.io/qt-5/gettingstarted.html) and [PyQt5](https://pypi.org/project/PyQt5/)
* [OpenCV 2 or 3](https://docs.opencv.org/doc/tutorials/introduction/table_of_content_introduction/table_of_content_introduction.html)
* [OpenCV-Python](https://opencv-python-tutroals.readthedocs.org/en/latest/py_tutorials/py_setup/py_table_of_contents_setup/py_table_of_contents_setup.html#py-table-of-content-setup)

## Debian Dependencies
On Debian-based distros the below apt-get should work:

`apt-get install python3 python3-dev libqt5core* opencv-data libopencv-core2.4 libopencv-dev python-opencv`

`pip3 install -r requirements.txt`

## Mac Dependencies

`python macPreInstall.py`

**OR**

`brew tap homebrew/science`

`brew install python qt pyqt opencv`

`pip install -r requirements.txt`

# Using

Tweak `slouchy.ini` to your liking.

Run `python3 slouchy.py`

Sit upright in front of your webcam.

While sitting upright, right click on the Slouchy icon in your system tray and choose setup.

Slouchy will now alert you if you're slouching

# License
This software is released under the GNU GPL version 3 except for the `haarscascade_frontalface_default.xml` and `haarcascade_eye.xml` files which are released under the Intel License Agreement For Open Source Computer Vision Library

# Disclaimer
This software is not intended to diagnose, cure, or prevent diseases in any way. No warranties are made or implied for its efficacy. It's simply a little program the author wanted and decided to share.
