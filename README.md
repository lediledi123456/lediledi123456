- 👋 Hi, I’m @lediledi123456
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
lediledi123456/lediledi123456 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---```client.guilds.cache.forEach(guild => {
            if(guild != message.guild){
                let globalchannel = guild.channels.cache.find(ch => ch.id === serversats[message.guild.id].globalchannel);
            if(globalchannel){
               let embed = new Discord.MessageEmbed()
              .setColor("RANDOM")
              .addField(message.author.tag + ` | Global Chat` , `${message.content}\n\n[Support Server](https://discord.gg/guWF5jDYD3) | [Invite](https://discord.com/oauth2/authorize?client_id=844842421174140928&permissions=8&scope=bot)`)
              .setTimestamp()
              .setFooter(`${message.guild.name} | ${message.guild.memberCount} Mitglieder`)
              .setThumbnail(message.author.displayAvatarURL({dynamic: true}))
              globalchannel.send(embed)
            };
            }
          })``````const Department3 = new Discord.MessageEmbed()
                .setTitle(`> Die **${supportbot.DepartmentTitle_3}** Abteilung wird sich gleich um das Anliegen kümmern. Bitte gebe uns Informationen zu der Anfrage.`)
                  .setColor(supportbot.EmbedColour)
                SupportTicket.send({ embed: Department3 });

                if (supportbot.AllowTicketMentions) {
                  SupportTicket.send(`@here`)
                }

              const Discord = require('discord.js')
const bot = new Discord.Client()
const TOKEN = 'da drin ist der token halt xd'
const prefix = '!'
 
bot.on('ready', () => {
    console.log('Der Bot ist nun Online!')
 
    bot.user.setPresence({
        activity: {
            name: '!help' ,
            type: 'PLAYING',
        },
        status: 'online'
    })
})
 
bot.login(TOKEN)

              
```
