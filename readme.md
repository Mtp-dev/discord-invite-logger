# **Discord Invite Logger Bot - Discord.js v13**

The Discord Invite Logger Bot allows you to track invites on your Discord server. It enables you to see which member invited a user to your server. It provides an exceptional interface using buttons, one of Discord's latest features.

## ⭐ **Don't forget to star the project!**

---

## **Installation (LOCALHOST)**

<details>
<summary>Steps to Install Locally</summary>

1. Install [Node.js](https://nodejs.org/en/).
2. Run the file **`install.bat`** to install the required dependencies.
3. Create a new application on the [Discord Developer Portal](https://discordapp.com/developers/applications/), enable the bot option in the **Bot** tab, and copy the bot token.
4. At the bottom of the **Bot** tab, enable the **SERVER MEMBERS INTENT** option.
   ![Server Members Intent](https://i.imgur.com/ywbvEv0.png)
5. Use the **OAuth2** tab to generate an invitation link for your bot.
6. Open the **`config.json`** file and fill in the required information.
7. Enter your bot token in the **`.env`** file.
8. Start the bot by double-clicking the **`start.bat`** file.
9. If you have any questions or issues, open an issue on GitHub under **[Issues](https://github.com/azynux/discord-invite-logger/issues)** or **[join the Discord server](https://discord.gg/QTswMhEeFd)**.
10. Below are placeholders you can use in the message configuration of the **`config.json`** file:
   ```
   {user} : Mention the new member
   {userName} : Username of the new member
   {userTag} : Tag of the new member
   {createdAt} : Account creation date of the new member
   {createdTimestamp} : Time since the account was created
   {inviteCode} : Code of the invitation used to join
   {memberCount} : Member count (excluding bots)
   {inviter} : Mention the inviter
   {inviterName} : Username of the inviter
   {inviterTag} : Tag of the inviter
   {inviteCount} : Number of invites by the inviter
   ```
</details>

---

## **Installation (Hosting with Pterodactyl)**

<details>
<summary>Steps to Install with Pterodactyl</summary>

1. Create a new application on the [Discord Developer Portal](https://discordapp.com/developers/applications/), enable the bot option in the **Bot** tab, and copy the bot token.
2. At the bottom of the **Bot** tab, enable the **SERVER MEMBERS INTENT** option.
   ![Server Members Intent](https://i.imgur.com/ywbvEv0.png)
3. Use the **OAuth2** tab to generate an invitation link for your bot.
4. Upload all files and folders to the **File Manager** tab in your Pterodactyl panel.
5. Open the **`config.json`** file and fill in the required information.
6. Enter your bot token in the **`.env`** file.
7. In the **Startup** tab, set the `BOT JS FILE` field to `src/index.js`.
8. Go to the **Console** tab and start the bot.
9. If you have any questions or issues, open an issue on GitHub under **[Issues](https://github.com/azynux/discord-invite-logger/issues)** or **[join the Discord server](https://discord.gg/QTswMhEeFd)**.
10. Below are placeholders you can use in the message configuration of the **`config.json`** file:
   ```
   {user} : Mention the new member
   {userName} : Username of the new member
   {userTag} : Tag of the new member
   {createdAt} : Account creation date of the new member
   {createdTimestamp} : Time since the account was created
   {inviteCode} : Code of the invitation used to join
   {memberCount} : Member count (excluding bots)
   {inviter} : Mention the inviter
   {inviterName} : Username of the inviter
   {inviterTag} : Tag of the inviter
   {inviteCount} : Number of invites by the inviter
   ```
</details>

---

## **See Also**
- [Discord Suggestions Manager Bot](https://github.com/azynux/discord-suggestions-bot)

---

### **More features coming soon... Stay tuned!**

__**Join Me on Discord ([Click Here](https://discord.gg/QTswMhEeFd)):**__

[![Discord Link](https://cms-assets.tutsplus.com/cdn-cgi/image/width=850/uploads/users/1631/posts/34139/image/Twitch%20Panel%20Maker%20for%20a%20Simple%20Chat%20Button%20copy.jpg)](https://discord.gg/QTswMhEeFd)
