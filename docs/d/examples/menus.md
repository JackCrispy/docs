
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
    .setMaxValues(5)
    .setMinValues(1)
    .setPlaceholder('Click me! :D');
    .addOption(option)
```

<img align="center" src="https://cdn.discordapp.com/attachments/850457799422771270/861212725484716032/unknown.png"></img>