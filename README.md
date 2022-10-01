# PokeMeow With PyTorch

A farm bot for Pokemeow. Solves captcha with custom trained weights with YOLOv5 and PyTorch. 

Youtube Channel : https://www.youtube.com/channel/UCHh6ndnVUl-jkQpvqRsFtvg

### Prerequisites :
- Install latest version of from microsoft store. https://apps.microsoft.com/store/detail/python-310/9PJPW5LDXLZ5?hl=en-us&gl=US
- Install Git https://git-scm.com/downloads
- On Ubuntu: sudo apt install libgl1-mesa-glx

### Install Visual C++ Redistributable

Link: https://aka.ms/vs/16/release/vc_redist.x64.exe

### Enable Long Paths in Windows Powershell (Run as Administrator):

```
New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" -Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force
```

### Installation with terminal :

```
# Drag PokeTorch-main.zip onto Desktop and double click on it.

# Open terminal and change directory
cd PokeTorch-main

# Install python requirements
python -m pip install -r requirements.txt

```


### Edit config.py

Authorization:

Find auth token by watching this video:

https://www.youtube.com/watch?v=YEgFvgg7ZPI

Or put this code in discord console:

```
(webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!==void 0).exports.default.getToken()
```

Channel Id is the last section of this url. Guild id is the first: ex (discord.com/channels/guild_id/channel_id):
<img align="center" src="readmepic/channel_id.png" width="1000">

Rename config-sample.json to config.json.


### Run:

To start farming, in terminal type:

```
python main.py
```




