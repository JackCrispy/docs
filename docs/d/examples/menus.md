
# Menus

## Menu
```js
let option = new MessageMenuOption()
    .setLabel('Your Label')
    .setEmoji('🍔')
    .setValue('menuid')
    .setDescription('Custom Description!')
    
let select = new MessageMenu()
    .setID('customid')
    .setPlaceholder('Click me! :D')
    .setMaxValues(1)
    .setMinValues(1)
    .addOption(option)

message.channel.send('Text with menu!', select);
```

<img align="center" src="https://cdn.discordapp.com/attachments/850457799422771270/861212725484716032/unknown.png"></img>
