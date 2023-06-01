# Web Server written in micropython for a Raspberry Pi Pico W

![Version 1.0.0](https://img.shields.io/badge/version-v1.0.0-blue)
[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg)
[![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg)
[![Python 3.6 | 3.7 | 3.8](https://img.shields.io/badge/python-3.6%20|%20%203.7%20|%203.8-yellowgreen)](https://www.python.org/downloads/release/python-385/)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

[![Vim](https://img.shields.io/badge/--019733?logo=vim)](https://www.vim.org/)
[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![GPL license](https://img.shields.io/badge/License-GPL-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

Web Server written in micropython for a Raspberry Pi Pico W 2 - Wifi - BT

By Computer Science Engineer: Felipe A. Gonzalez <f.alfonso@res-ear.ch>

If you like my project, give it a :star: or support me by buying me a coffee :coffee::grinning:

<a href="https://www.buymeacoffee.com/felipealfonsog" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 27px !important;width: 114px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>


### Important Notice
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">You can buy for about 10 or 15 USD a Raspberry Pi Pico in Aliexpress 🧵</p>&mdash; - May 28, 2023</blockquote>

---

### Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
    - [To Run it](#to-run)
    - [To Host](#to-host)
- [Instructions](#instructions)
  - [File Structure](#file-structure)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [Creator / Maintainer](#creator--maintainer)
- [Additional Information](#additional-information)

---

## Getting Started

Get a raspberry pi pico w 2 - wifi. Get a usb - micro-c cable and get thonny IDE.

![Raspberry Pi Pico](resources-for-readme/raspberry-pi-pico.jpg)

### Prerequisites

#### To Run it

- [Python 3](https://www.python.org/downloads/)
- [Thonny](https://thonny.org) - a micropython IDE

#### To Host

You can host it locally, or directly when it's connected via USB, but that implementation is not yet properly working fine.

It can be used to host a site 24/7. Also has a implementation for a 404 file not find, like most webservers. 

---

## Instructions

1. Get thony IDE and modify the network connectivity. 

2. Run the file setting up Thonny to run the code as a raspberry pi pico

- Make sure you have uploaded the files in the raspberry.

4. Run the script!

```
webserver.py
```

### File Structure

```
Web server in micro-python
 |-- webserver.py
 |-- default.html 
```

---

## Deployment

Here is a tutorial on how to deploy 


[Additional Information](#additional-information) for details on running the script continuously.
    - 

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate. But i would prefer if you could contact me first. 

### How To Contribute

1. Fork the repository to your own Github account.
2. Clone the project to your machine.
3. Create a branch locally with a succinct but descriptive name. You can use 'development' directly. 
4. Commit changes to the branch.
5. Following any formatting and testing guidelines specific to this repo.
6. Push changes to your fork.
7. Open a Pull Request in my repository - Before start a conversation.

-For Development, use the development branch and then we can do a pull request to the main branch. use : git --help for swtiching ... e.g.:
```
felipe@Felipes-MacBook-Air webserver-raspberry-pico % git branch development
felipe@Felipes-MacBook-Air webserver-raspberry-pico % git branch        
  development
  * main
felipe@Felipes-MacBook-Air webserver-raspberry-pico % git checkout development
```
When git push for 'development':
```
git push --set-upstream origin development
git branch --set-upstream-to=origin development

git clone -b <branchname> <remote-repo-url>
```

---

### Creator / Maintainer
Computer Science Engineer:
Felipe Alfonso González L. ([felipealfonsog](https://github.com/felipealfonsog))

If you have any questions, comments, or concerns, feel free to contact me below.

<p align="left">
  <a href="mailto:felipe.alfonso.glz@gmail.com"> 
    <img alt="Connect via Email" src="https://img.shields.io/badge/Gmail-c14438?style=flat&logo=Gmail&logoColor=white" />
  </a>
</p>

This project was created for educational purposes of learning development, documentation, and deployment and for personal and open-source use.

Default values of the project are used to /

If you like my content or find this code useful, give it a :star: or support me by buying me a coffee :coffee::grinning:

<a href="https://www.buymeacoffee.com/felipealfonsog" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

---

## Additional Information

- [Getting Started with Thonny](https://thonny.org/)
- [How to Continuously Run a Python Script on an EC2 Server](https://intellipaat.com/community/9361/how-to-continuously-run-a-python-script-on-an-ec2-server)
