<p align="center">
  <h1 align="center">Simple DRPС</h1>
</p>
<p align="center">
  <h2 align="center">Simple Discord Rich Presence client</h2>
</p>
<p align="center">
  <a href="https://github.com/OctoBanon-Main/discord-rpc-client/issues">Send bug report</a>
  •
  <a href="https://github.com/OctoBanon-Main/discord-rpc-client#how-use-this">Usage</a>
  •
  <a href="https://github.com/OctoBanon-Main/discord-rpc-client#something-is-broken-right-now">Broked features</a>
  •
  <a href="https://github.com/OctoBanon-Main/discord-rpc-client#special-thanks">Special thanks</a>
  •
  <a href="https://github.com/OctoBanon-Main/discord-rpc-client#licenses">Licenses</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/contributors/OctoBanon-Main/discord-rpc-client?style=for-the-badge"/>
  <img src="https://img.shields.io/github/forks/OctoBanon-Main/discord-rpc-client?style=for-the-badge"/>
  <img src="https://img.shields.io/github/stars/OctoBanon-Main/discord-rpc-client?style=for-the-badge"/>
  <img src="https://img.shields.io/github/issues/OctoBanon-Main/discord-rpc-client?style=for-the-badge"/>
  <img src="https://img.shields.io/github/downloads/OctoBanon-Main/discord-rpc-client/total?style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/OctoBanon-Main/discord-rpc-client?style=for-the-badge"/>
</p>
<br />

## Warning
Argument parser will be rewrited in next update and old arguments maybe will unavalible or renamed

## How use this?
- Install pypresence with command:
```bash
pip install pypresence
```
Or on linux
```bash
pip3 install pypresence
```
- Create application in [Discord Developer Portal](https://discord.com/developers/applications)

- Take application id from your created app and paste this in client-id argument

- Create profile with command:
```bash
python main.py create --client-id ID --name "NAME" --details "TEXT" --state "TEXT"
```
- And load this with command
```bash
python main.py load --name "NAME"
```
Addictional arguments will be in help
```
python main.py --help or -h
```
```
python main.py create --help or -h
```

## Something is broken right now
Nothing is broken

## How I can help?
Feel free to fork this repo and make a pull request or create an issue, if you encountered a problem!

## Special thanks
[.ZΞRO](https://github.com/kostya-zero) - For helping with code and bug fixing

vnpleo - For helping with text correction in this readme

## Licenses
The project is licensed under the GNU General Public License 3.0.
