# electron-store-todolist-demo 🐳

![Stars](https://img.shields.io/github/stars/tquangdo/electron-store-todolist-demo?color=f05340)
![Issues](https://img.shields.io/github/issues/tquangdo/electron-store-todolist-demo?color=f05340)
![Forks](https://img.shields.io/github/forks/tquangdo/electron-store-todolist-demo?color=f05340)
[![Report an issue](https://img.shields.io/badge/Support-Issues-green)](https://github.com/tquangdo/electron-store-todolist-demo/issues/new)

# reference
- [qiita1](https://qiita.com/udayaan/items/2a7c8fd0771d4d995b69#electron--react%E3%81%A7todo%E3%82%A2%E3%83%97%E3%83%AA%E3%82%92%E4%BD%9C%E3%82%8B)
- [qiita2](https://qiita.com/udayaan/items/dfb324bc6cadeb9a8f6f#electron%E3%82%92%E5%8B%95%E3%81%8B%E3%81%97%E3%81%A6%E3%81%BF%E3%82%8B)

# qiita1

## build
1. ### clone
	```shell
	git clone --depth=1 \
	https://github.com/electron-react-boilerplate/electron-react-boilerplate \
	your-project-name

	cd your-project-name

	npm install
	npm start
	```
1. ### use electron-store
	```shell
	npm install electron-store
	```
	- add `// ~~~~~~~~ start(end)` code in `src/renderer/App.tsx`, `src/main/preload.ts` & `src/main/main.ts`
	![store](screenshot/store.png)
	- run `npm start`
	![run](screenshot/run.png)
	- json data will auto be saved in `/Users/do.tranquang/Library/Application Support/Electron/config.json`
1. ### build package
	```shell
	npm run package
	```
	![build](screenshot/build.png)

# qiita2

## build
```shell
mkdir DTQElectron && cd DTQElectron
npm init -y
npm install --save-dev electron
npm start
# Electron Forge
npm install --save-dev @electron-forge/cli
npx electron-forge import
# build app file
npm run make
```

## build image
![make_build](screenshot/make_build.png)
