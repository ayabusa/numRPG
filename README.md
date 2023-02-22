# NumRPG
I might finish this rpg one day, hopefully ...

## Build the app

To build this RPG app, you will need to install the [embedded ARM toolchain](https://developer.arm.com/Tools%20and%20Software/GNU%20Toolchain) and [Node.js](https://nodejs.org/en/). The C SDK for Epsilon apps is shipped as an npm module called [nwlink](https://www.npmjs.com/package/nwlink) that will automatically be installed at compile time.

```shell
brew install numworks/tap/arm-none-eabi-gcc node # Or equivalent on your OS
make clean && make build
```

You should now have a `output/NumRPG.nwa` file that you can distribute! Anyone can now install it on their calculator from the [NumWorks online uploader](https://my.numworks.com/apps).

## Issue
If you encounter any bug or problem or you just want to talk to me here is my discord : ayabusa#6813

## Nice projects
Nice projects that you should definitly check out.
- [Upsilon](https://getupsilon.web.app/)
- [Omega](https://getomega.dev/)
- [Nwagyu](https://www.nwagyu.com/)

## License

Use it as you want bro just credit me pls