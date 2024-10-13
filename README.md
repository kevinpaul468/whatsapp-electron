# Whatsapp-electron
A Electron appliction that helps you run whatsapp web like a native application
<br>
Purpose : its main purpose is to bring a <b>customisable</b> whatsapp application especially for linux

installing dependencies
```
npm i
npm i -g electron
```

testing
```
npm start
```
building
```
npm i -g electron-packager
# electron-packager . "your app name here" --arch="your arch"
electron-packager . whatsapp-electron --arch=x64
```
linux installation
```
sudo mv whatsapp-electron-linux-64 /usr/share/
sudo mv whatsapp-electron.desktop /usr/share/applications
```

