# KartRider.Translator

This repository contains the translation files used by the KartRider Translator app which translates Asian versions of
KartRider into English as good as possible.

## How does it work?

To make this possible, a patch file is created / downloaded which supports the following patch actions:

- Merging English text into string bags which are used in KartRider to reference translated text.
- Merging other XML-like data into game files which can be referenced by XPaths.
- Replacing any files (used to replace images and textures containing text).

The patch files are seperated by KartRider region and are placed in the `res` folder.
Only Korean KartRider is correctly supported at the moment.

## Where do I get the translator app?

You can download the most recent Translator app on the [Discord server](https://discord.gg/3ddF5UP), where you can also
feel free to ask questions on how to use it and how to contribute to the translations.
