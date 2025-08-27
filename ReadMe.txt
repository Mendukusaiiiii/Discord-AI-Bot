Discord AI Bot

ABOUT:
A Python based Discord bot that leverages the OpenRouter API for AI-generated responses.


Features:
- Specified user memory
- Channel lock/unlock setup
- Simplified prefix commands

PROJECT FILES:
1. bot.py           - Main Python script that runs the bot.
2. config.json      - Configuration file (API key, model, and settings).
3. requirements.txt - Python dependencies for Katabump or local hosting.

SETUP INSTRUCTIONS:

STEP 1: Edit `config.json`

Open the `config.json` file and update the following:
- `"api_key"`: Replace with your OpenRouter API key (line 2)
- `"system_context"`: Customize the assistant personality (line 4)
- `"error_message"`: Change the fallback message shown on error (line 5)

STEP 2: Edit `bot.py`
- At the bottom, replace `<YOUR_BOT_TOKEN>` with your Bot Token.

STATUS : (bot.py line 35-36) 
- status=discord.Status.online #Options: online, idle, dnd, invisible
- activity=discord..., name="<YOUR_STATUS_MESSAGE>"),