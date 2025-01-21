# MCFormat.JS

## 🎯Usage
``` js
let str = `
§nMinecraft Formatting

§r§00 §11 §22 §33
§44 §55 §66 §77
§88 §99 §aa §bb
§cc §dd §ee §ff

§r§0k §kMinecraft
§rl §lMinecraft
§rm §mMinecraft
§rn §nMinecraft
§ro §oMinecraft
§rr §rMinecraft
`

let rez1 = MCFormat.parse(str)
let rez2 = MCFormat.parse(str.replace(/§/g,'&'),'&')

document.write(rez1 + '<br>')
document.write(rez2 + '<br>')
```
对 `§k` 无效