# Androidjs-builder
---
This is official builder for creating [Androidjs](https://android-js.github.io/) apps. Builder provides required commands for creating Androidjs project and to build the project and generate Apk for [android](https://developer.android.com/about) devices.

## Installing from [npm](https://www.npmjs.com/). [![androidjs-builder][androidjs-builder-badge]][androidjs-builder-npm]
```bash
$ npm install -g androidjs-builder
```
This command installs the builder in globelly and sets the required commands.

## Creating Project.
```bash
$ androidjs init
```
This command is used for generating new project in the current directory. This command prompts for [``project-name``](https://android-js.github.io/docs/configuring_app.html#change-the-name-of-your-app) and [``project-type``](https://android-js.github.io/docs/configuring_app.html#define-project-type). Currently it supports only the HTML type project.

## Build project
```bash
$ androidjs build
```
This command is used to build project and generate Apk file. It can be used to build all type of projects supported by Androidjs.


[androidjs-builder-badge]: https://img.shields.io/badge/Androidjs-builder-green.svg
[androidjs-builder-npm]: https://www.npmjs.com/package/androidjs-builder
[androidjs-builder-github]: https://github.com/android-js/androidjs-builder