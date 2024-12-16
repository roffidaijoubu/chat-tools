<h1 align="center">OrionChat</h1>
<div align="center">
<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge"/>
<img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99" alt="Star Badge"/>
<a href="https://discord.gg/JgjExyntw4"><img src="https://img.shields.io/discord/733027681184251937.svg?style=flat&label=Join%20Community&color=7289DA" alt="Join Community Badge"/></a>
<a href="https://twitter.com/oristarium"><img src="https://img.shields.io/twitter/follow/oristarium.svg?style=social" /></a>
<br>

<i>A powerful OBS integration tool for managing live stream chats with TTS and avatar animations</i>

<a href="https://github.com/oristarium/orionchat/stargazers"><img src="https://img.shields.io/github/stars/oristarium/orionchat" alt="Stars Badge"/></a>
<a href="https://github.com/oristarium/orionchat/network/members"><img src="https://img.shields.io/github/forks/oristarium/orionchat" alt="Forks Badge"/></a>
<a href="https://github.com/oristarium/orionchat/pulls"><img src="https://img.shields.io/github/issues-pr/oristarium/orionchat" alt="Pull Requests Badge"/></a>
<a href="https://github.com/oristarium/orionchat/issues"><img src="https://img.shields.io/github/issues/oristarium/orionchat" alt="Issues Badge"/></a>
<a href="https://github.com/oristarium/orionchat/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/oristarium/orionchat?color=2b9348"></a>
<a href="https://github.com/oristarium/orionchat/blob/master/LICENSE"><img src="https://img.shields.io/github/license/oristarium/orionchat?color=2b9348" alt="License Badge"/></a>

</div>

## ✨ Features

- 🎮 **Easy OBS Integration** - Simple browser source setup for chat display and TTS avatar
- 🗣️ **Text-to-Speech** - Multi-language TTS support with customizable avatar animations
- 💬 **Multi-Platform Support** - Works with YouTube, TikTok, and Twitch
- 🎨 **Customizable Avatars** - Support for both static and animated avatars
- 🎯 **Real-time Chat Display** - Show highlighted messages on stream
- 🔧 **Control Panel** - User-friendly interface for managing all features

## 🚀 Quick Start

1. Download the latest release for your platform
2. Run the application
3. Open OBS and add the following browser sources:

```bash
Control Panel: http://localhost:7777
Chat Display: http://localhost:7777/display
TTS Avatar: http://localhost:7777/tts
```

## 📖 Setup Guide

### Control Panel Setup
- Add a new Custom Browser Dock in OBS
- Set URL to `http://localhost:7777`
- Name it "Chat Tools Control"

### Avatar TTS Setup
- Add a new Browser source
- Set URL to `http://localhost:7777/tts`
- Recommended size: 300x300

### Chat Display Setup
- Add a new Browser source
- Set URL to `http://localhost:7777/display`
- Recommended size: 400x600

## 🛠️ Configuration

### Supported Languages
- 🇮🇩 Indonesian
- 🇺🇸 English
- 🇰🇷 Korean
- 🇯🇵 Japanese

### Platform Support
- YouTube (Channel ID or Username or Live ID)
- TikTok (Username)
- Twitch (Username)

## 💖 Support

Love this project? Please consider supporting us:

<a href="https://trakteer.id/oristarium">
  <img src="https://cdn.trakteer.id/images/embed/trbtn-red-1.png" height="40" alt="Support us on Trakteer" />
</a>

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<h3 align="center">Made with ❤️ by</h3>
<div align="center">
<img alt="Oristarium Logo" src="https://ucarecdn.com/87bb45de-4a95-40d7-83c6-73866de942d5/-/crop/5518x2493/1408,2949/-/preview/1000x1000/" width="200"> </img>
</div>
