![logo](https://raw.githubusercontent.com/Azapru/AzureEngine/main/assets/logo.png "logo")
![](https://img.shields.io/github/stars/azapru/azureengine.svg) ![](https://img.shields.io/github/release/azapru/azureengine.md.svg) ![](https://img.shields.io/github/issues/azapru/azureengine.svg) ![](https://img.shields.io/github/repo-size/azapru/azureengine.svg)

# FNF Azure Engine Modding Guide
enjoy my bad modding guide :)) / sorry for bad english :(((((

## How To Start
To start modding Azure Engine you need these programs:
- Clickteam Fusion 2.5 (for code editing)
Get it here: https://www.clickteam.com/clickteam-fusion-2-5
- Audacity (for audio editing)
Download: https://www.audacityteam.org/

## Compiling
That's really easy...
![](https://raw.githubusercontent.com/Azapru/AzureEngine/main/assets/build.png)

## Charting Songs
**!! You need to first chart a song in normal FNF !!**
1. Get mp3 file of song you wanna chart and name it **editor.mp3** and put inside **songs/** folder
2. Run Azure Engine
3. Go to freeplay and click 7 on keyboard
4. Set scroll speed (35 recommended)
5. Set notes speed (click on "calculate notes speed" button, enter bpm of song, convert bpm and then divide length of 1 beat by 4, that's your notes speed) (**!! If you got number with "numbers after dot" read "Fixing Song Offset"**)
6.  Open normal FNF with chart you wanna have in Azure Engine
7. Copy all sections to Azure Engine chart editor manually (the hardest part, can take really long, remember to playtest sometime to make sure you copied it correctly)
![](https://raw.githubusercontent.com/Azapru/AzureEngine/main/assets/happy.png)
(im working on better solution :|| )

## Fixing Song Offset
**!! You need Audacity for this !!**
**Download Audacity: https://www.audacityteam.org/**
1. On BPM calculator page try adding +1 bpm and dividing "1 beat" by 4 until you get number with no "numbers after dot"
2. Open audacity
3. Open your song file in audacity
4, Click on effects > change tempo
5. Insert there old/original bpm (from) and new bpm (to)
6. Click OK
7. Now export the song to mp3

## Adding Characters/Backgrounds
1. Clone any character/background
![](https://raw.githubusercontent.com/Azapru/AzureEngine/main/assets/clone.png)
2. Setup all character's/background frames
3. (in event editor) Go to CHARACTERS and copy any chart (ctrl+c & ctrl+v)
4. Set chart to chart you want with this character/background
5. Set character/background visibility to this chart
![](https://raw.githubusercontent.com/Azapru/AzureEngine/main/assets/vis.png)

## Adding Songs To Freeplay
That's too hard to explain sorry but it's pretty simple, just look to the code sorry :|
