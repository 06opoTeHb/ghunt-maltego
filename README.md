# Ghunt-Maltego
### Maltego Transform Partner to Ghunt 

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

## 💎 About

Per their Github page, "[Ghunt (v2)](https://github.com/mxrch/GHunt) is an offensive Google framework, designed to evolve efficiently.
It's currently focused on OSINT, but any use related with Google is possible." Ghunt-Maltego utilizes the Ghunt python library to create Transforms in Maltego.

## 🎚️ Version
| Version                          | Supported          | Release Date |
|----------------------------------|--------------------|--------------|
| Ghunt-Maltego 1.0.x              | ✅                | TBD          |
| 🕰️ Ghunt-Maltego 1.0.0-beta      | ✅                | 2 June 2023  |

🕰️ *Current version*

## 🛠️ Setup
For more detailed instructions, read the [Wiki](https://github.com/kodamaChameleon/ghunt-maltego/wiki)
### Requirements
- Maltego 4.3.0
- Python 3.11.2
   - maltego-trx 1.6.0
   - ghunt 2.0.3
   - geocoder 1.38.1
 - A Gmail Account
 - Ghunt Firefox/Google Companion (Optional)
   
### Installation
```
   cd ~/.local/bin
   git clone https://github.com/kodamaChameleon/ghunt-maltego.git
   cd ghunt-maltego
   python3 setup.py
```

### Demo

<img src="img/ghunt.gif">  
   
## 🧙 Features
   
| Data Type       | Supported  |Entity             |
|-----------------|------------|-------------------| 
| Full Name       | ✅         | maltego.Person    |
| Profile Photos  | ✅         | maltego.Image     |
| Cover Photos    | ❌         |                   |
| User Type       | ❌         |                   |
| Gaia ID         | ❌         |                   |
| Enabled Apps    | ✅         |maltego.Service    |
| Review Company  | ✅         |maltego.Company    |
| Review Rating   | ✅         |maltego.Sentiment  |
| Review Type     | ✅         |maltego.Industry   |
| Review Tag      | ✅         |maltego.hashtag    |
| Review Location | ✅         |maltego.Location   |
| Review Photos   | ❌         |                   |
   
## 📜 License
![image](https://img.shields.io/badge/License-GNU%20GPL-blue)

[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.fr.html)
