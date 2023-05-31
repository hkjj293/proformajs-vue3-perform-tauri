# proformajs-vue3-perform-tauri

A template for desktop standalone PRO<i>formajs</i>-Vue3 project [Tauri](https://tauri.app/) + [Vite]() + [Vue3]()

The original component work for this project can be found at https://gitlab.com/openclinical/proformajs-vue3

---

This template should help get you started building standalone PRO<i>formajs</i>-Vue3 project with [Tauri](https://tauri.app/).

## Project Setup

###  Install system dependencies
- Please follow this [instruction](https://tauri.app/v1/guides/getting-started/prerequisites/) for installing dependencies.
 
###  Install development dependencies
```sh
npm install
```

## Debug standalone application using [Tauri](https://tauri.app/)

```sh
npm run tauri dev
```

## Package and distribution using [Electron Forge](https://www.electronforge.io/)

### Create bundles using command:
```sh
npm run tauri build
```

### Or with specific target platform: (e.g.)
```sh
npm run tauri build --target i686-pc-windows-msvc
```

### Output files
The executables should be output to `src-tauri/target/release` while bundles are in `src-tauri/target/release/bundle`
