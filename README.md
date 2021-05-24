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
          })```
