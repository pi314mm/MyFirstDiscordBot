First make a bot: https://discordapp.com/developers/applications/me

Then add bot to server: https://discordapp.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot&permissions=67584

create a auth.json file with the following info in it:

'''
{
  "token": "BOT-TOKEN",
  "prefix": "om"
}
'''

Install node.js

run `node bot.js`