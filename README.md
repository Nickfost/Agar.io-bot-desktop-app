### Description


This is an app built on `electron`, which uses web technologies on top of `nodejs`. It runs @Apostolique Agar.io bot.

### Installation

A few step are required to run this app.

***Firstly, clone this repo with `git clone`, or download it with the "Download as zip" button***

Currently, I couldn't find a way to pack everything in one file, so help is welcome.

Howerver, you only have to launch one file :

* On Windows :
    + Double click on `start.bat`
    + Inside the app directory, run the command `start.bat`
* On Mac OSX (**_To be confirmed_**) and Linux :
    + Double click on `start.sh`
    + Inside the app directory, run the command : `./start.sh`

### Advanced Installation

This is if you want to contribute or if you like to understand anything.

* On Windows, Linux, and Mac OSX:
    + Install `nodejs`
    + Then, in a comand prompt, run :

            npm install express
            npm install -g electron
            electron path_to_app_directory

### Thanks

* Thanks to **Apostolique** for the bot creation and for testing on windows.
* Thanks to **Designmodo** for the open-source `Flat-UI` CSS/JS theme.

### Troubleshooting

If you are having issues, please refer to this section before posting an issue

* **'_electron_' was not recognized as internal command'**
    + Download `electron` from the [official repository](https://github.com/atom/electron/releases).

    **_Make sure to select the right version!_** (`electron-v*-win32-ia32.zip` or `electron-v*-win64-x64.zip`)

    Then extract it somewhere, and add the path to your %PATH% environment variable.
* **Error: _Cannot find module 'express'_**
    + In a terminal/command prompt, go to the app directory, then run `npm install`.

    If this does not fix it, run `npm install express`
