<p align="center">
    <img width="350" height="350" src="https://timslab.de/timslab.png" alt="TimsLab Round">
    <br>
    <br>
    <br>
</p>

<p align="center">
    <a href="https://github.com/TimsLab">Github</a>&nbsp;&nbsp;&nbsp;
    <a href="https://twitter.com/TimsLabs">Twitter</a>&nbsp;&nbsp;&nbsp;
    <a href="https://discordapp.com/users/216297826081046528">Discord</a>&nbsp;&nbsp;&nbsp;
</p>

<br>

<br>

<p align="center">
  <sub>Built with ❤︎ by <a href="https://twitter.com/TimsLab">TimsLab</a></sub>
</p>
<br>

# TimsLab [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)


# 📜 Why do you need Discord-Spammer ?

You can flood Discord Servers with this Tool

# 💥 What does it do ?

- [x] Messagespammer
- [x] Joinspammer
- [x] Load Tokens

## Example
```js
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
});

client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});

client.login('token');
        
}
```
