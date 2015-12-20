# <p align="center">merbot

<p align="center">**A Telegram Group Peace Keeper Bot**


**Merbot** is Telegram group guardian bot based on [telegram-bot](https://github.com/yagop/telegram-bot) by [Yago Pérez](https://telegram.me/yago_perez) and [uzzbot](https://github.com/uziins/uzzbot) by [@silenceangel](https://telegram.me/silenceangel).

This is the testing branch to test addition of moderation system to merbot. 

1. **Autoleave**  
So the bot will kick itself when invited to unmanaged groups.
2. **Banhammer**  
Manage bans, kicks and white/black lists.
3. **Channels**  
Manage channels. Enable or disable channel.
4. **Greeter**  
Sends a custom message when a user enters or leave a chat.
5. **Group Manager**  
Manage group chat.
6. **Help**  
Help plugin. Get info from other plugins.
7. **Id**  
Know your id or the id of a chat members.
8. **Invite**  
Invite other user to the chat group.
9. **Moderation**  
Group moderation, i.e promote, demote and list administrators or moderators of a group.
10. **Plugins**  
Plugin to manage other plugins. Enable, disable or reload.
11. **Version**  
Shows bot version.

Consult [wiki](https://github.com/rizaumami/merbot/wiki/Plugins) to know how to use those plugins.

#### [Installation](https://github.com/rizaumami/merbot/wiki/Installation)

Check https://github.com/rizaumami/merbot/wiki/Installation to deploy `merbot` on your distributions.

#### Enable more [`plugins`](https://github.com/rizaumami/merbot/tree/master/plugins)

See the plugins list with `!plugins` command.

Enable a disabled plugin by `!plugins enable [name]`.

Disable an enabled plugin by `!plugins disable [name]`.

Those commands require a privileged user, privileged users are defined inside `data/config.lua` (generated by the bot), stop the bot and edit if necessary.

#### Contact me

Please open a [github issue](https://github.com/rizaumami/merbot/issues) if you found an issue with `merbot`.
Or you can contact me in [merbot discussion group](https://telegram.me/joinchat/AfB26wGZCncqP8GjKOhrcw).
