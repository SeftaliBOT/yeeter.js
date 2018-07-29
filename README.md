```js
const yeet = require("yeeter.js")
const yeeter = new yeet.Client()
yeeter.on("message", message => {
  if(message.content === '>ping'){
  message.channel.send("Pong!")
  }
})
yeeter.login('')
```
