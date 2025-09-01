# Kittu User-Bot

<div align="center">
  
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pyrogram](https://img.shields.io/badge/Pyrogram-2.0+-green.svg)](https://pyrogram.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-@Echo_Bug)](https://t.me/Echo_bug)

**A powerful, feature-rich Telegram userbot with versatile commands for automation, media management, and enhanced Telegram experience.**
**✨ Note: this code is bot ready code means you can run userbot as well use second client for bot for callbacks and functions ✨**

</div>

## ✨ Features

- 🔧 **Pro Commands** - Comprehensive command library
- 🤖 **Automation** - Auto replies, filters, scheduled tasks
- 💾 **Media Management** - Save, organize, and manage media files
- 🛡️ **Privacy & Security** - Ghost mode, anti-spam, user blocking
- 🎮 **Entertainment** - Games, jokes, ASCII art, and fun commands
- 🌐 **Search & Translation** - Multi-platform search and language tools
- 👑 **Administration** - Full group management capabilities
- 📝 **Notes & Reminders** - Personal productivity tools
- 🔌 **Custom Addons** - Extensible plugin system
- ⚡ **High Performance** - Fast and lightweight

## 📋 Complete Command List

### 👑 Administration Commands (22)
| Command | Usage | Description |
|---------|-------|-------------|
| `.ban` | `.ban [reply/user_id]` | Ban user from group |
| `.unban` | `.unban [user_id]` | Unban user from group |
| `.kick` | `.kick [reply/user_id]` | Kick user from group |
| `.promote` | `.promote [reply/user_id] [role]` | Promote user to admin |
| `.demote` | `.demote [reply/user_id]` | Demote admin to member |
| `.roles` | `.demote` | List the roles and usages |
| `.pin` | `.pin [reply]` | Pin replied message |
| `.unpin` | `.unpin [reply]` | Unpin replied message |
| `.vc` | `.vc` | Turn on voice chat |
| `.mute` | `.mute [reply/user_id] [time]` | Mute user for specified time |
| `.unmute` | `.unmute [reply/user_id]` | Unmute user |
| `.purge` | `.purge [reply]` | Delete messages from replied message |
| `.del` | `.del [reply]` | Delete replied message |
| `.lock` | `.lock [permission]` | Lock chat permissions |
| `.unlock` | `.unlock [permission]` | Unlock chat permissions |
| `.admins` | `.admins` | List all group admins |
| `.bots` | `.bots` | List all bots in group |
| `.users` | `.users` | List all users in group |
| `.zombies` | `.zombies` | Find deleted accounts |
| `.delservice` | `.delservice [on/off or direct` | Service messages deletion on off|
| `.keepservice` | `.keepservice [serive type eg. voice_chat]` | to keep service type from deletion |
| `.servicestatus` | `.servicestatus` | Get current status of deletion |
| `.settitle` | `.settitle [title]` | Set group title |
| `.restoretitle` | `.restoretitle` | Restore original title |
| `.welcome` | `.welcome [on/off] [msg]` | Set welcome message |
| `.goodbye` | `.goodbye [on/off] [msg]` | Set goodbye message |
| `.filter` | `.filter [trigger] [response]` | Add auto-response filter |
| `.filters` | `.filters` | List all active filters |
| `.stop` | `.stop [trigger]` | Remove filter |

### 💾 Media & Storage Commands (7)
| Command | Usage | Description |
|---------|-------|-------------|
| `.save` | `.save [reply]` | Save media file |
| `.get` | `.get [file_id]` | Retrieve saved file |
| `.files` | `.files` | List all saved files |
| `.delmedia` | `.delmedia [file_id]` | Delete saved media |
| `.cloud` | `.cloud` | Access cloud storage menu |
| `.backup` | `.backup` | Backup all userbot data |
| `.restore` | `.restore` | Restore from backup |

### 🛡️ Privacy & Security Commands (10)
| Command | Usage | Description |
|---------|-------|-------------|
| `.block` | `.block [reply/user_id]` | Block user |
| `.unblock` | `.unblock [user_id]` | Unblock user |
| `.blocked` | `.blocked` | List blocked users |
| `.afk` | `.afk [reason]` | Set AFK mode with reason |
| `.unafk` | `.unafk` | disable AFK mode |
| `.ghost` | `.ghost [on/off]` | Toggle ghost mode |
| `.antispam` | `.antispam [on/off]` | Toggle anti-spam protection |
| `.captcha` | `.captcha [on/off]` | Enable CAPTCHA for new users |
| `.report` | `.report [reply]` | Report message to admins |
| `.whitelist` | `.whitelist [user_id]` | Add user to whitelist |

### 🤖 Automation & Custom Commands (12)
| Command | Usage | Description |
|---------|-------|-------------|
| `.autoreply` | `.autoreply [trigger] [response]` | Set automatic reply |
| `.delreply` | `.delreply [trigger]` | Delete auto reply |
| `.replies` | `.replies` | List all auto replies |
| `.alias` | `.alias [name] [command]` | Create command alias |
| `.unalias` | `.unalias [name]` | Remove command alias |
| `.aliases` | `.aliases` | List all aliases |
| `.menu` | `.menu [name] [buttons]` | Create custom menu |
| `.menus` | `.menus` | List all custom menus |
| `.reaction` | `.reaction [trigger] [emoji]` | Set auto reaction |
| `.delreaction` | `.delreaction [trigger]` | Delete auto reaction |
| `.schedule` | `.schedule [time] [command]` | Schedule command execution |
| `.unschedule` | `.unschedule [id]` | Cancel scheduled task |
| `.tasks` | `.tasks` | List scheduled tasks |

### 📝 Notes & Reminders Commands (8)
| Command | Usage | Description |
|---------|-------|-------------|
| `.note` | `.note [name] [content]` | Save a note |
| `.getnote` | `.getnote [name]` | Retrieve saved note |
| `.delnote` | `.delnote [name]` | Delete note |
| `.notes` | `.notes` | List all saved notes |
| `.remind` | `.remind [time] [message]` | Set reminder |
| `.reminders` | `.reminders` | List all reminders |
| `.todo` | `.todo [task]` | Add task to todo list |
| `.todos` | `.todos` | List todo items |
| `.done` | `.done [id]` | Mark todo as completed |

### 🌐 Search & Translation Commands (11)
| Command | Usage | Description |
|---------|-------|-------------|
| `.search` | `.search [query]` | Search YouTube videos |
| `.tr` | `.tr [language] [text]` | Translate text |
| `.wiki` | `.wiki [query]` | Search Wikipedia |
| `.img` | `.img [query]` | Search images |
| `.weather` | `.weather [city]` | Get weather information |
| `.ud` | `.ud [word]` | Urban Dictionary lookup |
| `.define` | `.define [word]` | Dictionary definition |
| `.syn` | `.syn [word]` | Find synonyms |
| `.ant` | `.ant [word]` | Find antonyms |
| `.news` | `.news [category]` | Get latest news |
| `.rss` | `.rss [url]` | Add RSS feed |
| `.feeds` | `.feeds` | List RSS feeds |

### 👤 Profile & Presence Commands (10)
| Command | Usage | Description |
|---------|-------|-------------|
| `.setbio` | `.setbio [text]` | Set profile bio |
| `.setpic` | `.setpic [reply/photo]` | Set profile picture |
| `.setname` | `.setname [first] [last]` | Set display name |
| `.username` | `.username [username]` | Set username |
| `.qr` | `.qr [text]` | Generate QR code |
| `.readqr` | `.readqr [reply]` | Read QR code |
| `.avatar` | `.avatar [user_id]` | Get user avatar |
| `.status` | `.status [text]` | Set custom status |
| `.clone` | `.clone [user_id]` | Clone user profile |
| `.revert` | `.revert` | Revert profile changes |

### 🎮 Entertainment & Fun Commands (23)
| Command | Usage | Description |
|---------|-------|-------------|
| `.quote` | `.quote` | Get random quote |
| `.addquote` | `.addquote [text]` | Add custom quote |
| `.delquote` | `.delquote [id]` | Delete custom quote |
| `.myquotes` | `.myquotes` | List your quotes |
| `.joke` | `.joke` | Get random joke |
| `.fact` | `.fact` | Get random fact |
| `.meme` | `.meme` | Get random meme |
| `.ascii` | `.ascii [text]` | Convert text to ASCII art |
| `.reverse` | `.reverse [text]` | Reverse text |
| `.mock` | `.mock [text]` | Create mocking text |
| `.vapor` | `.vapor [text]` | Convert to vaporwave text |
| `.clap` | `.clap [text]` | Add claps between words |
| `.emojify` | `.emojify [text]` | Add random emojis |
| `.spoiler` | `.spoiler [text]` | Create spoiler text |
| `.password` | `.password [length]` | Generate random password |
| `.hash` | `.hash [text]` | Generate text hash |
| `.base64` | `.base64 [encode/decode] [text]` | Base64 encoding/decoding |
| `.leet` | `.leet [text]` | Convert to 1337 speak |
| `.flip` | `.flip [text]` | Flip text upside down |
| `.cowsay` | `.cowsay [text]` | ASCII cow says text |
| `.roll` | `.roll [dice]` | Roll dice |
| `.8ball` | `.8ball [question]` | Magic 8 ball |
| `.choose` | `.choose [option1\|option2]` | Random choice picker |

### ⚙️ Utilities & Tools Commands (22)
| Command | Usage | Description |
|---------|-------|-------------|
| `.calc` | `.calc [expression]` | Calculator |
| `.ping` | `.ping` | Check bot response time |
| `.leave` | `.leave` | Leave current chat |
| `.echo` | `.echo [text]` | Echo message |
| `.type` | `.type [text]` | Typing animation |
| `.alive` | `.alive` | Check bot status |
| `.short` | `.short [url]` | Shorten URL |
| `.expand` | `.expand [url]` | Expand shortened URL |
| `.spb` | `.spb [user_id]` | Check SpamWatch ban |
| `.whois` | `.whois [user_id]` | Advanced user information |
| `.id` | `.id [reply/user_id]` | Get user/chat IDs |
| `.info` | `.info [reply/user_id]` | Detailed user info |
| `.stats` | `.stats` | Group statistics |
| `.invite` | `.invite [user_id]` | Invite user to group |
| `.export` | `.export [chat_id]` | Export chat members |
| `.import` | `.import [file]` | Import member list |
| `.ss` | `.ss [url]` | Take website screenshot |
| `.currency` | `.currency [amount] [from] [to]` | Currency converter |
| `.time` | `.time [location]` | Get current time |
| `.domain` | `.domain [domain]` | Domain information |
| `.ip` | `.ip [ip_address]` | IP address lookup |
| `.whoisdomain` | `.whoisdomain [domain]` | Whois domain lookup |

### 🔧 Developer & Advanced Commands (12)
| Command | Usage | Description |
|---------|-------|-------------|
| `.eval` | `.eval [code]` | Evaluate Python code |
| `.exec` | `.exec [code]` | Execute Python code |
| `.shell` | `.shell [command]` | Execute shell command |
| `.restart` | `.restart` | Restart userbot |
| `.update` | `.update` | Update userbot |
| `.logs` | `.logs` | Get bot logs |
| `.sysinfo` | `.sysinfo` | System information |
| `.speedtest` | `.speedtest` | Network speed test |
| `.pingall` | `.pingall` | Ping all group members |
| `.broadcast` | `.broadcast [message]` | Broadcast message |
| `.cleanup` | `.cleanup` | Clean temporary files |
| `.debug` | `.debug [on/off]` | Toggle debug mode |

### 📱 Custom Addons Commands (6)
| Command | Usage | Description |
|---------|-------|-------------|
| `.addon` | `.addon [name]` | Load custom addon |
| `.addons` | `.addons` | List available addons |
| `.createaddon` | `.createaddon [name]` | Create new addon |
| `.editaddon` | `.editaddon [name]` | Edit existing addon |
| `.deleteaddon` | `.deleteaddon [name]` | Delete addon |
| `.reloadaddons` | `.reloadaddons` | Reload all addons |

**Total: 120+ Commands across 11 categories**

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- Telegram API credentials
- Unsplash API key (optional, for image features)


**Deploy the service**

### VPS Deployment (Ubuntu/Debian)

1st. **Clone and setup**
   ```bash
   git clone https://github.com/BtwUnnati/user && cd user
   
   pip3 install -r requirements.txt
   ```

3. **Configure environment**
   ```bash
   nano config.py  # Edit with your credentials
   ```

4. **Run with screen (persistent session)**
   ```bash
   screen -S userbot
   python3 main.py
   # Press Ctrl+A then D to detach
   ```

## 🧪 Tested Version

- **Python**: 3.8, 3.9, 3.10, 3.11
- **Pyrogram**: 2.0+
- **Platform**: Linux, Windows, macOS
- **Telegram**: Latest stable version

