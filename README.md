# 2019_Robot (Apollo)
Team 3172's WIP FRC python code.

- ![](https://i.imgur.com/Uu2L0cb.png)
- [Colorado Regional FRC](https://www.thebluealliance.com/team/3172/2019#2019code) current status

## Robot Setup
1. Install required libs
```bash
pip install -r requirements.txt
```
2. Download both `robotpy` and `cscore` _(cscore needed for cameras)_
```bash
robotpy-installer download-robotpy
robotpy-installer download-opkg python37-robotpy-cscore
```
3. Connect RoboRIO to computer and install `robotpy` and `cscore`
```bash
robotpy-installer install-robotpy
robotpy-installer install-opkg python37-robotpy-cscore
```
Robot is now ready for code to be deployed!
