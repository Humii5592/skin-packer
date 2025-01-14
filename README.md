# Skin Packer for Minecraft Education Edition

This form was developed so that those who use Minecraft's Education Edition (who may have not used Mojang's online store) could easily compile the respective JSON files and information without worrying too much about the code, and UUIDs and all the other complicated stuff.

Link to the skin packer: https://mattheffnt.github.io/skin-packer/

## Features

This is a form where a user inputs the respective details for their skin file, uploads their custom skin PNG file and the MCPack is generated for them.In version two, users can now add multiple skins to their MCPack. Users can also now see their skin in realtime and how it will look in-game.

Additionally, I've made a batch script for Windows users that is an easy automated way to delete any custom skinpacks that the user may have imported into Minecraft Education Edition.

Simply run the following command in command prompt, this will download the batch script to your Desktop, then follow the instructions.

```
  cd %homepath%/Desktop
  curl https://raw.githubusercontent.com/MattHeffNT/skin-packer/master/removeSkins.bat -o removeSkins.bat
  removeSkins.bat
  
```
  
When I get time I'll add a script for Linux and OSX.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## To Do

-   Getting a "required field" tool tip when add skin button pressed....also need to improve UX as can be confusing to user when they've pressed add skin button and "nothing" seems to happen.

## Acknowledgements

Just wanted to give a big thank you to the creators of the react-skinview3d package (link below), and for working with me through some of the issues in intergrating it into this app.

https://github.com/Hacksore/react-skinview3d

## License

MIT © [MattHeffNT](https://github.com/MattHeffNT)
