# AudioTAG
Audio tagging export XML


Electron app - requires electron <br />
Nodejs plugins - xmlbuilder, fs

## Installing
for use in npm scripts
npm install electron-packager --save-dev

for use from cli
npm install electron-packager -g

npm install --save-dev electron

# Build
## MacOS
electron-packager . --overwrite --platform=darwin --arch=x64 --icon=assets/icons/mac/logo.icns --prune=true --out=release-builds

## Windows
electron-packager . electron-tutorial-app --overwrite --asar=true --platform=win32 --arch=ia32 --icon=assets/icons/win/logo.ico --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="AudioTAG"
