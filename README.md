# proformajs-vue3-perform-tauri

The original component work for this project can be found at https://gitlab.com/openclinical/proformajs-vue3

---

This template should help get you started building standalone PRO<i>formajs</i>-Vue3 project.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Project Setup

1. Install Rust and Cargo
    For windows:
    Download rustup installer via this [link](https://win.rustup.rs/)

    For Liux & MacOS:
    Use the following command:
    ```sh
    curl https://sh.rustup.rs -sSf | sh
    ```

2.
```sh
npm install
npm run build
```

## Debug standalone application using [Electron](https://www.electronjs.org/)

```sh
npm start
```

## Package and distribution using [Electron Forge](https://www.electronforge.io/)

1. Create distrubtion using make command.

```sh
npm run make
```

2. The executables should be output to `out` folder under the root folder of the project.
