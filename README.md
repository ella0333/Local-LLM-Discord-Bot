# Local LLM Discord Bot

🤖 Chat with your local LLM through Discord! Access your Ollama or LM Studio LLM from your phone, tablet, or any device with Discord.

## ✨ Features

- 🦙 **Works with Ollama & LM Studio** - Use your favorite local LLM
- 💬 **Natural Chat Interface** - DM the bot directly or mention it in servers
- 🛡️ **Optional Moderation** - OpenAI's free content filter
- 🔒 **User Whitelisting** - Control who can access your LLM
- 👥 **Smart Context Management** - Automatic single/multi-user modes
- 💾 **Saves Your Setup** - Configure once, use forever
- 🧠 **Conversation Memory** - Smart context window that shifts as needed
- 🖼️ **Vision Model Support** - Send images to vision-capable models
- 📝 **Chat Logging** - Save conversations for fine-tuning datasets
- 👍 **RLHF Data Collection** - Log user feedback for reinforcement learning

## 🚀 Quick Start

### Prerequisites

- Windows PC with Python 3.10+
- Ollama or LM Studio installed with at least one model
- Discord account

### Installation

```bash
git clone https://github.com/ella0333/Local-LLM-Discord-Bot.git
cd Local-LLM-Discord-Bot
pip install -r requirements.txt
python main.py
```

The setup wizard will walk you through everything! Just follow the prompts to configure your bot.

## 📖 **[Full Setup Guide](SETUP_GUIDE.md)**

For detailed instructions including Discord bot creation, whitelisting, and optional features to support your fine tuning pipeline, check out the full setup guide linked above.

## 💬 How to Use on Discord

Once set up, you can chat with your LLM like another user:

- **In Discord Servers:** Mention @BotName or reply to its messages
- **In DMs:** Right-click the bot in a server → "Message" to start a DM
- **With Images:** Feel free to send images to vision models!

The bot responds naturally - no commands needed! Though `/chat`, `/clear`, `/status` and `/help` are available if you prefer.

## 🆘 Troubleshooting

Having issues? Check out the **[Troubleshooting Guide](TROUBLESHOOTING.md)** for solutions to common problems.

## The Developer

Created with ❤️ by Gabriella Baris - Check out my [portfolio](http://www.gabriellabaris.com/) for more projects and tools!
And check out my current AI safety project [elif else](https://elifelse.com/)

## 📚 Contact & Support

If you have any issues, find bugs, or need assistance, please [open a GitHub issue](https://github.com/ella0333/Local-LLM-Discord-Bot/issues):
- Technical support
- Feature requests
- Bug reports
- General questions

## 📄 License

MIT License - Free to use and modify!

## 🙏 Credits

- [Ollama](https://ollama.ai) - Local LLM runner
- [LM Studio](https://lmstudio.ai) - LLM interface  
- [discord.py](https://discordpy.readthedocs.io/) - Discord API wrapper
- [OpenAI](https://openai.com) - Moderation API
