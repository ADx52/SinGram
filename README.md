## •  SinGram 🔎

[![Python3](https://img.shields.io/badge/language-Python3-red)](https://img.shields.io/badge/language-Python3-red)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-blue.svg)](https://t.me/ADx52)
[![Docker](https://img.shields.io/badge/Docker-Supported-blue)](https://img.shields.io/badge/Docker-Supported-blue)

<p align="center">
  <img src="https://raw.githubusercontent.com/ADx52/SinGram/master/.lib/SinGram.jpg" width="300" height="120">
</p>
<p align="center">
</p>
<p align="center"><img src="https://img.shields.io/badge/Version-5.2-brightgreen"></p>
<p align="center">
  <a href="https://github.com/ADx52">
    <img src="https://img.shields.io/github/followers/ADx52?label=Follow&style=social">
  </a>
  <a href="https://github.com/ADx52/SinGram/stargazers">
    <img src="https://img.shields.io/github/stars/ADx52/SinGram?style=social">
  </a>
</p>
<p align="center">
  Open Source Information Instagram
</p>

---

* The SinGram Tool for gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

* The information includes :

* [ profile ] : user id, followers / following, number of uploads, profile img URL, external URL, joined Recently, etc

* [ tags & mentions ]  : most used hashtags and mentioned accounts

* [ email ] : if any email is used any where it'll be displayed

* [ posts ] : accessability caption, location, timestamp, caption, picture url, etc
  * ( yet not working correctly with posts instagram marks as 'sensitive cotent' )  

---

## • How To Install

`$ pkg update && pkg upgrade -y`

`$ pkg install python3 -y`

`$ pkg install git -y`

`$ git clone https://github.com/ADx52/SinGram`

`$ cd SinGram`

`$ python3 -m pip install -r requirements.txt`

## • Usage

`$ python3 main.py -u username`

`$ python3 main.py -h`

`-p [{--post} images info highlight]`
