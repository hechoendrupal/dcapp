# dcapp

A cross platform UI for [Drupal Console](https://drupalconsole.com/)

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/willwh/dcapp
# Go into the repository
cd dcapp
# Install dependencies and run the app
npm install && npm start
```

## Tools

Currently we're using [shelljs](https://github.com/shelljs/shelljs) to run console via the main process.

Messaging between the main process and the renderer process is being done using [ipc-main](https://github.com/atom/electron/blob/master/docs/api/ipc-main.md) and [ipc-renderer](https://github.com/atom/electron/blob/master/docs/api/ipc-renderer.md)

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

## Chat

Come and chat with us in [Gitter.im](https://github.com/hechoendrupal/DrupalConsole)

#### License [CC0 (Public Domain)](LICENSE.md)