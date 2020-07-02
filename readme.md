# How to debug TypeScript with VS Code

Debugando Typescript no VSCode.

![debug-typescript-vscode](https://user-images.githubusercontent.com/1257048/86402536-5f5e3000-bc82-11ea-89ab-406b5e860a5e.png)

Veja as configuração de `.vscode/launch.json` a seguir.


### name: Launch Program

Esta configuração executa a aplicação.

Precisa buildar o projeto antes de executá-la.

    npm build

Coloque um breakpoint em alguma parte de código e "voilá".


### name: Build Project

Esta configuração "builda" e executa.

Dá para debugar também.


### Fonte

https://medium.com/@PhilippKief/how-to-debug-typescript-with-vs-code-9cec93b4ae56