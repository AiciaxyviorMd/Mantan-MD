#Mantan-Md

Danil (Clara-Md)
david (itsrose-Api's)
surya (nasXebot)
alicia ( saya sendiri)


## CATATAN ##
Script ini gratis untuk semua orang, bukan untuk Dijual. Jika dijual neraka menunggumu Brother!!

## Installation

1. Install [Node.js](https://nodejs.org/en/download/)
2. Install [Git](https://git-scm.com/downloads)
3. Clone this repository

```bash
git clone https://github.com/xct007
```

4. Install the dependencies

```bash
npm install
```
## Writing Plugin

1. Create a file named `plugin_name.js` in `plugins` folder
2. Edit `plugin_name.js` and fill in the values like this:

   ```js
   const handler = async (m, { conn, text, args, usedPrefix, plugins }) => {
     // your code here
   };

   handler.command = ["command"];
   handler.tags = ["tags"];
   handler.help = ["help"];

   export default handler;
   ```

3. Is it same as like [games-wabot](https://github.com/BochilGaming/games-wabot/tree/multi-device)? Yes, it is.

## Expanding

If you have `base code` that using something you call `case` and you want to use it in this source code, you can do this:

1. Edit file in `case/index.js`
2. Fill what you want to do
3. Edit `config.js` and set `use_case` to `true`

But remember, the `base code` must be using `Baileys` API.

Advantages:
- The code in `case/index.js` will be executed before the plugin is executed.
- If the command is same in `plugin` and `case/index.js`, the `case/index.js` will be executed first.

I recommend to migrate your `base code` to the way plugins are written.
## Disclaimer

This repository project is using other open source projects. No warranties are made as to the usability of the source code contained herein. Any use of this code is subject to an understanding that the code itself is not guaranteed to be fit for any particular purpose and the user is solely responsible for any repercussions of its use. No guarantee is given as to the accuracy or correctness of the results obtained from using the code in this repository. 

This repository project uses other open source projects, the authors or owners of which may have different license terms from the code contained in this repository. You should consult the individual license terms of those projects before using the code. 

The authors and maintainers of this repository project are not responsible for any damage or loss arising from the use of the code contained herein. Use the code at your own risk.

## Contributing

You can contribute in many ways:
```
1. Report bugs
2. Give suggestions
3. Fork and make pull request
```
You can add more features, fix bugs, or anything else.

### Thanks To **

**Allah SWT**,

**Orang Tua**,

**Semua yang selalu mendukung**
[Baileys](https://github.com/WhiskeySockets/Baileys)
[Baileys](https://github.com/WhiskeySockets/Baileys)
[Alicia](https://github.com/AiciaxyviorMd)
[zeltoria](https://github.com/Zeltoria)
[david.stefen(https://github.com/Davidrose)
[surajana](https://github.com/nat9h)
