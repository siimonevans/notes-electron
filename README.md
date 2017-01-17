#Notes (Electron)

An electron-based version of the [Notes PWA](https://github.com/SimonDEvans/notes), with UI changes for desktop app usage.

<img src="https://sii.im/playground/notes/notes-electron.png" alt="Notes app" width='512px'>

## To Use

From your command line:

```bash
# Clone this repository
git clone git@github.com:SimonDEvans/notes-electron.git
# Go into the repository
cd notes-electron
# Install dependencies
npm install
# Run the app
npm start
```

## Packaging and distribution

By default, DevTools is open. Prevent this by removing `mainWindow.webContents.openDevTools()` in `notes-electron/main.js`.

To easily create an executable OS-specific bundle (.app, .exe etc), I reccommend using [electron-packager](https://github.com/electron-userland/electron-packager). 

A more in-depth explanation and method can be found at the [official application distrubition guidelines.](https://github.com/electron/electron/blob/master/docs/tutorial/application-distribution.md#packaging-your-app-into-a-file)

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/).
