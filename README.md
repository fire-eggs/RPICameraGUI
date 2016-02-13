RPICameraGUI
============

Simple graphical interface for taking photos on the Raspberry Pi Camera

Written python 2.7 for the Raspberry Pi


1. Requires wxPython 2.8. Will not run with anything newer.
2. Assumes a 10 point font (or smaller?). If you've set your desktop font larger, the layout will be buggered.

```shell
sudo apt-get install -y python-wxgtk2.8 python-wxtools python-wxversion
wget https://raw.github.com/fire-eggs/RPICameraGUI/master/RPICameraGUI.py
python RPICameraGUI.py
```
