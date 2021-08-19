# ultroiduserbot

UltroidAddons

Plugins repository for Ultroid.

Contributing

If you want to contribute to this repository (adding your plugins/porting from other bots), use the format given below and create a pull request.
⚠️ First check whether the stuff you push works. Also, if the pull request doesn't follow the below format, it will be closed without prior notice.

# Credits @username (creator of plugin and who ported) # Ported from (if ported else skip) # Ported for Ultroid < https://github.com/ArchitThakur2611/ultroiduserbot  > 

Kindly do not steal others works without credits.

Example Plugin

Required Import are Automatically Done.

This Example Works Everywhere. (e.g. Groups, Personal Chats ...)

@ultroid_cmd(pattern="hoi") async def hello_world_example(event): # As telethon is an asyncio based lib, you will have to use await. # The Default Parse Mode Is MarkDown V2 await event.reply("Hello World.")

This Example Works Only In Groups.

@ultroid_cmd(pattern="hoi", groups_only=True,) async def hello_world_example(event): await event.reply("Hello World.")

If Your plugin need any additional requirements, it can be added to addons.txt

Made with 💕 by @Archit_26
