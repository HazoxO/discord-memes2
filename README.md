<h1 align="center">
  <br>
  <a href="https://github.com/HazoxO/discord-memes2"><img src="https://w.wallhaven.cc/full/8x/wallhaven-8x7qj2.jpg" alt="Discord-Memes 2"></a>
  <br>
  Discord-Memes 2
  <br>
</h<h4 align="center">Un módulo para hacer memes para tu bot de discord.</h4>

<p align="center">
  <a href="https://discordapp.com/invite/7ZsYdpuF">
    <img src="https://discordapp.com/api/guilds/845459731308347442/widget.png?style=shield" alt="Discord Server">
  </a>
  <a href="https://github.com/discordjs/discord.js">
     <img src="https://img.shields.io/badge/discord-js-blue.svg" alt="discord.js">
  </a>

  # Instalacion 
  
 ```js
  npm i discord-memes2
 ```
  
  # Uso normal
  
  ```js
 const memes = require("discord-memes2"); 
console.log(memes.imagenesEspañol())
  ```
  
  # Ejemplo dentro del index
  
   ```js
 
  const memes = require('discord-memes2');
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
    console.log('Listo!')
});

client.on('message', (message) => {
    if (message.content == 'meme') {
        message.channel.send(memes.imagenesEspañol())
    }
});

client.login('token');
 ```
  
  # Otros usos de metodos
  
  memes.imagenesEspañol() retorna imagenes de memes en español.

  memes.videosEspañol() retorna videos de memes en español.

  memes.deTodoEspañol() retorna de todo (videos e imagenes) en español.
  
  # Nota
  
  Esto fue tomado de proyecto discord-memes de dylan pero este se estara actualizando cada semana llenandose de mas memes para todos!
  https://github.com/Dylan-Pro/discordmemes
 
