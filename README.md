![Mod-Logo](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/ModPreview_512.jpg)

# XCOM 2 Community Translation Mod

This is a community project for gathering all translations for other XCOM 2 mods in one place. Anyone can submit their translation for any existing mod, and it will be added to the Community Translation Mod.

For translators, it is more convenient and reliable than asking individual mod authors to add their translations to their mods.

For mod users, it is more convenient, because they can use just one translation mod.

## I am a mod user, how do I use this?

Subscribe to the mod on the **[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3001342800)**, wait for Steam to download the mod, then activate it in your mod launcher.

If you are using a non-Steam version of the game, download the `X2CommunityTranslation.zip` from the **[latest release](https://github.com/X2CommunitySupplemental/X2CommunityTranslation/releases/latest)** page and follow **[these instructions](https://www.reddit.com/r/xcom2mods/wiki/index/download_mods#wiki_how_to_install_mods_manually)** to install it manually.

## What mods are translated?

The list of translated mods **[is here](https://github.com/X2CommunitySupplemental/X2CommunityTranslation/blob/main/List_of_translated_mods.md)**.

## I am a translator, how do I submit my translation?

Submissions are handled via GitHub interface. See **[this video](https://youtu.be/nMVHwzMoyjw)** for an example or follow step-by-step instructions below.

1. Sign into your GitHub account. **[Sign up](https://github.com/join)** if you don't have one.
2. Follow **[this link](https://github.com/X2CommunitySupplemental/X2CommunityTranslation/tree/main/X2CommunityTranslation/Localization)** to open this mod's Localization folder.
3. In the top right, click **Add file -> Create new file**.

![Instruction_1](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_1.png)

If this is your first submission on this account, you will be asked to fork the repository. Simply click the **"Fork this repository"** green button.

![Instruction_0](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_0.png)

4. In the top bar, you will see "Name your file" text field. Use the following template: `ModName/FileName.Extension`

![Instruction_2](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_2.png)

**ModName** - the name of the mod's .XComMod file without the extension. Translation for each individual mod should exist in its own folder to make it easy to find and modify.

If needed, you can add more folders after ModName.

**FileName** - name of the localized file.

**Extension** - depends on the language you're adding the translation for:

* int - International English
* chn - Simplified Chinese
* cht - Traditional Chinese
* deu - Deutch (German)
* esn - Espanjol (Spanish)
* fra - French
* ita - Italian
* jpn - Japanese
* kor - Korean
* pol - Polish
* rus - Russian

5. Enter the translated text into the main window and click the green button "Commit changes"

![Instruction_3](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_3.png)

6. In the Commit message text field, use the template: `<workshop mod name> - <language>`, then click the green button "Propose changes".

![Instruction_4](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_4.png)

7. A new page will open. Click the green button "Create pull request".

![Instruction_5](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_5a.png)

8. You will be redirected to another page. Once again, click the green button "Create pull request".
  
![Instruction_5b](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_5b.png)

10. Click **[this link](https://github.com/X2CommunitySupplemental/X2CommunityTranslation/edit/main/List_of_translated_mods.md)** to edit the file with the list of translated mods.

If the list doesn't already have an entry for the mod that you have added translation for, then add it. 
The entry needs to contain the mod's workshop name, prefaced with a `#` symbol, and a workshop link to the mod on the next line, followed by an empty line.

Then add the language you have added translation for to the list of languages under the mod name. The language name must be prefaced by a `*` symbol.

![Instruction_6](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_6.png)

9. Same as before, click "Commit changes", but this time do not change the commit message. Once again, click "Propose changes".

![Instruction_7](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_7.png)

Then click "Create pull request" on both of the next pages.

10. All done. Wait for maintainers to review your pull request and upload the update to Steam Workshop. This process may take a few days.

## How do I update an existing translation?

Open the file you wish to edit, then click the **pencil icon** to enter editing mode.

![Instruction_8](https://raw.githubusercontent.com/X2CommunitySupplemental/X2CommunityTranslation/main/Img/Instruction_8.png)

Once you're done, click the green button "Commit changes" and follow the process explained above to submit a pull request.
