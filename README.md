[license-badge]: https://img.shields.io/github/license/ClearVision/ClearVision-v7?style=flat-square
[license-link]: https://github.com/asilverstorm/CrystalClearVision/blob/master/LICENSE
[discord-badge]: https://dcbadge.limes.pink/api/shield/594371388228239370
[discord-link]: https://discordapp.com/users/594371388228239370

<div align="center">

# CrystalClearVision v1.1.3

[![Discord][discord-badge]][discord-link]  
[![License][license-badge]][license-link]


![Example](https://i.imgur.com/kcrkRrc.jpeg)

</div>

# About the Project

This is a fork of the BetterDiscord Theme ClearVision that I have just customized to my liking. My customizations include removing the background images and making the window transparent, removing the ClearVision Branding, setting different UI colors, and overall readability improvements (specifically with dropdown menus).

## CrystalVision + Known Issues w/ CrystalClearVision

In the [dist](https://github.com/asilverstorm/CrystalClearVision/tree/master/dist) folder of this repo, you may have noticed a theme file named CrystalVision. This is what I use right now, and is basically me giving up on working on CrystalClearVision for a little bit. CrystalVision is NOT transparent, but fixes the following known issues with CrystalClearVision:

- Overall laggy window behavior
- Images/videos opened will be persistent instead of closing when you want them to
- User profiles / other drop-down menus are hard to read due to the background of those also being transparent and having the rest of the Discord window visible behind them
- Not compatible with Windows 10/11 window-snapping
- Removes rounded / native OS window border

Feel free to use it, or put in a pull-request if you have a fix to any of those issues within CrystalClearVision. I will review them all.


## Installing

For BetterDiscord:
 [releases] Download CrystalClearVision from [HERE](https://github.com/asilverstorm/CrystalClearVision/tree/master/dist) and move the file directly into BetterDiscord's themes folder @ `%appdata%\rbetterdiscord\themes`


### 3rd Party Dependencies

- [NodeJS/npm](https://nodejs.org/)
- [pnpm](https://www.npmjs.com/package/pnpm)
- [sass](https://www.npmjs.com/package/sass)
- [PostCSS Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)

I just ran `npm install` and that seemed to work so imma not care about pnpm. Also I'm just straight up editing the already compiled files from the original src code so that folder is really just here to refer back to if needed.

## Support
Join the original ClearVision [discord server](https://discord.gg/dHaSxn3) and post in their support channel if you need additional help with your own customization!  
Special Thanks to gitlimes for his project that allowed me to easily get my own Discord Badge for this README. You can view this resource [HERE](https://github.com/gitlimes/dcbadge?tab=readme-ov-file#user-account)

### Disclaimer
!! ASSUME CHANGES HAVE BEEN MADE TO ALL FILES IN THIS REPOSITORY BY ASILVERSTORM !!  
(This disclaimer is made in an effort to be compliant with the Apache License the original work is distributed under)