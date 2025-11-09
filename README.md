
---

<div align="center">
  <h1 align="center">
    <img src="icon.png" width="200"/>
    <br/>
    ok-ww
  </h1> 
<h3><i>Image recognition-based automation for Wuthering Waves, uses Windows interface to simulate user clicks, no reading game memory or invasive modification of game files/data.</i></h3>
</div>

![Static Badge](https://img.shields.io/badge/platfrom-Windows-blue?color=blue)
[![GitHub release (with filter)](https://img.shields.io/github/v/release/ok-oldking/ok-wuthering-waves)](https://github.com/ok-oldking/ok-wuthering-waves/releases)
[![GitHub all releases](https://img.shields.io/github/downloads/ok-oldking/ok-wuthering-waves/total)](https://github.com/ok-oldking/ok-wuthering-waves/releases)
[![Discord](https://img.shields.io/discord/296598043787132928?color=5865f2&label=%20Discord)](https://discord.gg/vVyCatEBgA)

### [English Readme](README_en.md) | Chinese README

Demo and Tutorial [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/h6P1KWjdnB4)

# Disclaimer

This software is an external tool designed to automate Wuthering Waves gameplay. It only interacts with the game through the existing user interface and complies with relevant laws and regulations. This software package is meant to make it easier for users to interact with the game - it doesn't break game balance or give unfair advantages, and it doesn't modify any game files or code.

This software is open source, free, and for personal learning and communication purposes only. It's limited to personal game accounts and cannot be used for any commercial or profit-making purposes. The dev team has final say on interpretation of this project. Any problems that arise from using this software have nothing to do with this project or the dev team. If you find merchants using this software for account boosting services and charging money, that's the merchant's own behavior - this software is not authorized for boosting services, and any problems or consequences from that have nothing to do with this software. This software doesn't authorize anyone to sell it - software being sold might have malicious code added that could steal your game account or computer info, which has nothing to do with this software.

Please note, according to Kuro Games' Wuthering Waves Fair Play Statement:

```
Using any third-party tools to disrupt the game experience is strictly prohibited.
We will crack down hard on the use of cheats, speed hacks, cheat software, macro scripts and other rule-breaking tools. These behaviors include but are not limited to auto-farming, skill acceleration, invincibility mode, teleporting, modifying game data, etc.
Once verified, depending on the severity and frequency of violations, we will take measures including but not limited to removing illegally obtained gains, freezing or permanently banning game accounts.
```

### How to Use: Download the portable 7z compressed package (around 250MB), extract and double-click ok-ww.exe

* [GitHub Download](https://github.com/ok-oldking/ok-wuthering-waves/releases), free direct web link, don't click download Source Code, click to download the 7z package
* [Mirror-chan Download Channel](https://mirrorchyan.com/zh/projects?rid=okww&source=ok-ww-readme), domestic direct web link, need to purchase CD-KEY to download, free download if you already have Mirror-chan CD-KEY
* [Quark Cloud Drive](https://pan.quark.cn/s/a1052cec4d13), free, but requires registration and downloading Quark cloud drive client
* After joining QQ channel, download from discussion group [https://pd.qq.com/s/djmm6l44y](https://pd.qq.com/s/djmm6l44y)

### How powerful is it?

1. Runs smoothly at 4K resolution, supports all 16:9 resolutions 1600x900 and above. 1280x720 isn't supported because of a Wuthering Waves bug - their 1280x720 isn't actually 1280x720. Some features also work on 21:9 ultrawide resolutions
2. Can run in background, windowed or fullscreen, no screen scaling requirements
3. Auto-recognizes all characters, no need to configure combo sequences, one-click operation
4. Auto-mutes game in background

### If you have problems, check these

Got issues? Click here and check each one before asking questions:

1. **Installation:** Install to a directory containing only English characters, cannot install in Program Files directory.
2. **Antivirus interference:** Add download and extraction directories to your antivirus software/Windows Defender whitelist.
3. **Display settings:** Turn off GPU filters and sharpening. Use default game brightness and disable FPS overlays on the game (like MSI Afterburner).
4. **Custom keybinds:** If not using default keys, configure them in APP settings. Keys not in settings are not supported.
5. **Outdated version:** Make sure you're using the latest version of OK-WW.
6. **Performance:** Maintain stable 60 FPS in game, lower resolution if needed.
7. **Game disconnects:** If you frequently experience server connection issues, try opening the game for 5 minutes before starting to play, or if disconnected don't exit the game, just log back in
8. **Further help:** If the problem persists, please submit a bug report.

### Running from Python Source

Only supports Python 3.12

```
pip install -r requirements.txt --upgrade #install python dependencies, may need to rerun after updating code
python main.py # run the release version
python main_debug.py # run the debug version
```

### Command Line Arguments

```
ok-ww.exe -t 1 -e
```

- -t or --task means auto-execute task number after startup, 1 is the first task, the all-in-one task
- -e or --exit means auto-exit after completing tasks

### Join Us

* Wuthering Waves chat group 462079653, group entrance answer: Old Wang classmate OK
* If group is full join QQ channel [https://pd.qq.com/s/djmm6l44y](https://pd.qq.com/s/djmm6l44y)
* Developed based on [ok-script](https://github.com/ok-oldking/ok-script), project code is only 3000 lines (Python), simple and easy to maintain. You're also welcome to use ok-script to develop your own projects
* Development guide and docs [https://github.com/ok-oldking/ok-script](https://github.com/ok-oldking/ok-script)
* If interested in development please join dev group 926858895. At minimum you need to be able to read docs and run from source code. People asking usage questions or making feature requests will get kicked

### Related Projects

* [ok-sra](https://github.com/Shasnow/ok-starrailassistant) Honkai: Star Rail automation based on ok-script

* [ok-genshin-impact](https://github.com/ok-oldking/ok-genshin-impact) Genshin Impact automation based on ok-script, one-click dailies, background story mode (can run in background, supports all game languages, supports all 16:9 resolutions)
* [ok-gf2](https://github.com/ok-oldking/ok-gf2) Girls' Frontline 2 Exilium automation, one-click dailies, arena, neural simulation, dusty memories (supports PC version background mode)

## Sponsors

- EXE signing: Free code signing provided by [SignPath.io](https://signpath.io/), certificate by [SignPath Foundation](https://signpath.org/)

### Credits

* [https://github.com/lazydog28/mc_auto_boss](https://github.com/lazydog28/mc_auto_boss)
* [https://github.com/ok-oldking/OnnxOCR](https://github.com/ok-oldking/OnnxOCR)
* [https://github.com/zhiyiYo/PyQt-Fluent-Widgets](https://github.com/zhiyiYo/PyQt-Fluent-Widgets)
* [https://github.com/Toufool/AutoSplit](https://github.com/Toufool/AutoSplit)
