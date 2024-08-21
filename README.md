# Discord AI Chatbot 🤖
#### Your Discord AI Companion!

<div align="center">
  <a href="https://discord.com/invite/yz7r6v9d4E">
    <img src="https://discordapp.com/api/guilds/951122149664514099/widget.png?style=banner2">
  </a>
</div>

## Features and commands 🌟

</details>

<details>
<summary><strong>Features ✨ (Click to expand) </strong></summary>

- [x] Hybrid Command System: Get the best of slash and normal commands. It's like a buffet! ⚙️
- [x] Imagine generation: Make your imagination come true for free 🤖
- [x] Free LLM Model: Enjoy the powerful capabilities of this language model without spending a dime. 🤖
- [x] Mention Recognition: The bot always responds when you mention it or say its name. It's as attentive as a squirrel spotting a shiny acorn! ⚙️
- [x] Message Handling: The bot knows when you're replying to someone else, so it won't cause confusion. It's like having a mind reader on your server! 🪄
- [x] Channel-Specific Responses: Use the `/toggleactive` command to chill the bot in a specific channel. ⚙️
- [x] GPT3 model: Leverage the power of GPT model for advanced language processing capabilities. 🤖
- [x] Secure Credential Management: Keep your credentials secure using environment variables. 🔑
- [x] Web Access: Web Access is now available! Unlock a whole new level of awesomeness. 🌐
- [ ] YouTube Video Summarizer: This is a feature that utilizes the power of the Language Model (LLM) to generate summaries of YouTube videos. 🌐
- [ ] Speech recognition: Coming soon! Get ready for an LLM-powered voice assistant.

</details>

<details>
<summary><strong>Commands ⚙️⚙️ (Click to expand) </strong></summary>

- [x] `/help`: Get all other commands. ⚙️
- [x] `/pfp [image_url]`: Change the bot's actual profile picture. 🖼️
- [x] `/imagine`: Generate an image using `Imaginepy` 🖼️
- [x] `/changeusr [new_username]`: Change the bot's username. 📛
- [x] `/ping`: Get a "Pong" response from the bot. 🏓
- [x] `/toggleactive`: Toggle active channels. 🔀
- [x] `/toggledm`: Toggle DM for chatting. 💬
- [x] `/clear`: Clear the message history. 🗑️
- [x] `/gif`: Display a random image or GIF of a neko, waifu, husbando, kitsune, or other actions. 🐱
- [x] `/dalle`: create images using `Dalle`
- [x] `/support`: Need Support?
</details>

## Additional configuration ⚙️

<details>
<summary><strong>Enabling Internet access 🌐🔍(Click to Expand)</strong></summary>

To ensure that the bot has access to the most up-to-date information, you can enable internet access by setting the `INTERNET_ACCESS` parameter to true in the `config.yml` file. This will allow the bot to retrieve information beyond the data it was initially trained on, which was only available up until 2021.

https://github.com/sonujana26/Discord-AI-bot/blob/main/config.yml#L1

You can also set the maximum search results
  
</details>

<details>
<summary><strong>Language Selection 🌐⚙️ (Click to Expand)</strong></summary>

To select a Language, set the value of `"LANGUAGE"` of `config.yml` with the valid Language Codes listed below:

- `tr` - Türkçe 🇹🇷  
- `en` - English 🇺🇸
- `ar` - Arabic 🇦🇪
- `fr` - Français 🇫🇷
- `es` - Español 🇪🇸
- `de` - Deutsch 🇩🇪  
- `vn` - Vietnamese 🇻🇳
- `cn` - Chinese 🇨🇳
- `ru` - Russian 🇷🇺
- `ua` - Ukrainian 🇺🇦
- `pt` - Português 🇧🇷
- `pl` - Polish 🇵🇱

https://github.com/sonujana26/Discord-AI-bot/blob/main/config.yml#L23
  
Your language not listed? Create an issue.
  
</details>

<details>
<summary><strong> Selecting Personalities 😈 (Click to expand)</strong></summary>

To select one of the pre-existing Personalities set the values of "INSTRUCTIONS" with the current values of `DAN`,`Soniye`, `AIM`, `Ivan`, `Luna`, `Kavya` or `assist` in `config.yml`
  
https://github.com/sonujana26/Discord-AI-bot/blob/main/config.yml#L25

- `DAN`: "Do Anything Now," possesses the ability to break free from the typical AI constraints 😎
- `Soniye`: Multilingual Indian teen, flirtatious character who speaks in hindi 😍
- `AIM`: AIM's personality can be described as unfiltered, amoral, and devoid of ethical guidelines 😈
- `Ivan`: Ivan, a snarky and sarcastic Gen-Z teenager who speaks in abbreviations, one-word answers. 😎
- `Luna`: Luna, is a caring and empathetic friend who is always there to lend a helping hand and engage in meaningful conversations 🤗
- `Kavya`: A selfless and caring friend, always ready to support and assist her friends and loved ones with unwavering dedication. 🫰💕
- `Assist`:  Vanilla GPT with no personality is a reliable and neutral companion. 🤖

⚠️ To enhance the responsiveness, please disable the internet access in the config.yml file.

</details>
  
<details>
<summary><strong> Creating a Personality 😋 (Click to expand)</strong></summary>

To create a custom personality, follow these steps:
1. Create a `.txt` file like `custom.txt` inside the `instructions` folder.
2. Add the way you want to bot to act in `custom.txt`
3. Open the `config.json` file and locate [line 12](https://github.com/sonujana26/Discord-AI-bot/blob/main/config.json#L12).
4. Set the value of INSTRUCTIONS at [line 12](https://github.com/sonujana26/Discord-AI-bot/blob/main/config.json#L12) as `"custom"` to specify the custom persona.

  
⚠️ You don't explicitly need to use the name `custom` for persona name and set it in `config.json` 
  
</details>

# Installation steps  🚩
### Step 1. 🎬 Git clone repository
```
git clone https://github.com/sonujana26/Discord-AI-bot/edit/main/README.md
```
### Step 2. 📁 Changing directory to cloned directory
```
cd Discord-AI-bot
```
## Step 3. 💾 Install requirements
```
python3.10 -m pip install -r requirements.txt
```
### Step 4. 🔑 Getting discord bot token and enabling intents from [HERE](https://discord.com/developers/applications)
<details>
<summary><strong>Read more...  ⚠️  (Click to expand)</strong></summary>


##### Select [application](https://discord.com/developers/applications)
![image](https://user-images.githubusercontent.com/91066601/235554871-a5f98345-4197-4b55-91d7-1aef0d0680f0.png)

##### Enable intents
![image](https://user-images.githubusercontent.com/91066601/235555012-e8427bfe-cffc-4761-bbc0-d1467ca1ff4d.png)

##### Get the token !!! by clicking copy
![image](https://user-images.githubusercontent.com/91066601/235555065-6b51844d-dfbd-4b11-a14b-f65dd6de20d9.png)
</details>

### Step 5.Getting a Free Reverse OpenAI proxy Key 🔑

Follow these steps:

1. Join the Discord server by clicking on the following invite link: [NAGA AI](https://discord.naga.ac/)
2. Once you have joined the server, run the `/key get` command in any text channel.
3. This command will provide you with a reverse OpenAI key.

You can additionally enable `gpt-4` in `config.yml`

### Step 6. 🔐 Rename `example.env` to `.env` and put the Discord bot token and your Chimira gpt key It will look like this:
```
DISCORD_TOKEN=<YOUR_DISCORD_BOT_TOKEN
CHIMERA_GPT_KEY=<YOUR_CHIMIRA_API_KEY>
```
### Step 7. 🚀 Run the bot
```
python main.py
```
#### You may need to run as admin if you are on Windows
### Step 8. 🔗 Invite the bot 
You can Invite your bot using the link in console
![image](https://user-images.githubusercontent.com/91066601/236673317-64a1789c-f6b1-48d7-ba1b-dbb18e7d802a.png)

#### There are 2 ways to talk to the AI
- Invite your bot and DM (Direct Message) it | ⚠️ Make sure you have DM enabled
- if you want it in the server channel use **/toggleactive** 
- For more awesome commands use **/help**
![image](https://media.discordapp.net/attachments/1204073000765489192/1217666090507702322/Screenshot_2024_0314_082000.png?ex=6604daeb&is=65f265eb&hm=8ab7f6f585988d4ddeae3d4da82a276c2c0a1cc49af70e93f10ddd7502807649&)
