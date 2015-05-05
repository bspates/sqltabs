# PGTABS

Tabbed SQL interface for Postrgesql.

![](/pgtabs.png?raw=true)

## Building
Project is under development. There are no platform builds provided yet.

In order to make a custom build follow the following steps.

Install [npm](https://www.npmjs.com).
Install [electron](http://electron.atom.io)

    npm install electron-prebuilt -g

Install jsx

    npm install -g jsx

Run (replace 0.25.2 with electron version you have):

    git clone https://github.com/sasha-alias/pgtabs
    cd pgtabs
    npm install
    npm install --save-dev electron-rebuild
    ./node_modules/.bin/electron-rebuild --version 0.25.2
    jsx src/ build/

    electron .

## Using

There are two basic shortcuts:

Action              | Windows and Linux | OSX 
--------------------|-------------------|--------------------
run script          | **Ctrl+R**        | **Command+R**
break execution     | **Ctrl+B**        | **Command+B**
