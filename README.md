# Sandboxels modding tutorial
This tutorial is going to be helpful for people who don't know how to mod for Sandboxels.

## Installing the game locally
To install Sandboxels locally, you have to download it from the [Sandboxels Github page](https://www.github.com/R74nCom/sandboxels). After extracting the ZIP file, open `index.html`, and now you're ready to test your mods!

Also, when coding, it is recommended to use a text editor like Notepad++, or any other text editor that has autocomplete support.

## Creating a mod
In the `mods` folder, create a file with a `.js` extension. This can be done in windows by replacing the `.txt` extension with the `.js` extension. The mod name should be something like `name_of_mod.js`, spaces are supported, but it is not recommended to use them.

To create an element, please follow the template below.
```
elements.test_element = {
    color: "ff00ff",
    name: "Whatever Name",
    behavior: behaviors.WALL,
    category: "land",
    state: "solid",
}
```
This creates a solid element with the color purple.

To test out the mod, just type the name of your mod file into the mod manager in Sandboxels, then reload to see changes.
