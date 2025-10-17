# Bots.Business Test Project

This is a test project downloaded from Bots.Business API for testing VS Code extension functionality.

# Project Structure

- `commands/` - Bot commands with CMD metadata blocks
- `.bbusiness/bot.json` - Bot configuration

# Commands

- `/start` - Main start command
- `/start1777` - Test command
- `start1` - Simple command
- `151/start12` - Command in folder

# CMD Blocks

Each command file contains a CMD block with metadata:

    command: /command_name

    help: Command description
    need_reply: false
    auto_retry_time: 
    folder: 
    answer: 
    keyboard: 
    aliases: 
    group: 
    updated_at: 2025-10-15T03:40:39.143Z
    folder_id: 
    CMD*/

# Command code here

# Testing

Mhis project is used for testing:

1. Download from Bots.Business API
2. Upload to GitHub
3. Download from GitHub
4. Verify CMD blocks preservation