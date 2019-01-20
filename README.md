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

run from file directory
# Build
## MacOS
electron-packager . --overwrite --platform=darwin --arch=x64 --icon=logo.icns --prune=true --out=release-builds

## Windows
electron-packager . AudioXML --overwrite --asar=true --platform=win32 --arch=ia32 --icon=logo.ico --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="AudioXML"
