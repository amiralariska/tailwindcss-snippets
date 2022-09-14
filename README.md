<p align="center">
    <img src="https://xp.io/storage/2yKfyjeM.png" width="250px" height="250px" alt="Tailwind CSS Logo">
    <h1 align="center">Tailwind CSS Snippets For VSCODE</h1>
    <p align="center">Create a TailwindCSS Project Using Snippets</p>
</p>

## Installation
### How To Install Tailwind CSS Snippets Extension
1. In the left sidebar click on the extension icon
2. Typing Tailwind CSS Snippets Snippets
3. And click on the install Button
4. And now your tailwindcss snippets has been installed
5. Done.

### How to Setup TailwindCSS In HTML Using TailwindCSS Snippets
1. Create a Folder, For Example:
[![Folder Example](https://xp.io/storage/2r2pi50e.png)](https://xp.io/storage/2r2pi50e.png)
2. Right click on the folder and click "Open With Code"
[![Open With Code](https://xp.io/storage/2vrtORkt.gif)](https://xp.io/storage/2vrtORkt.gif)
3. Press `` ctrl+` `` to toggle the terminal
[![Toggle Terminal](https://xp.io/storage/2vrImqKw.gif)](https://code.visualstudio.com/docs/terminal/basics)
4. And then typing `npm init -y` or `npm init` in the terminal, it will generate the package.json file
[![Create NPM Package](https://xp.io/storage/2vsb8oqW.gif)](https://docs.npmjs.com/cli/v8/commands/npm-init)
5. Create index.html file and then type exclamation point and hit enter
[![Create html file](https://xp.io/storage/2vsiqRUe.gif)](https://xp.io/storage/2vsiqRUe.gif)
6. Create a css file with src folder and then type `@tb` this will create tailwindcss basic boilerplate
[![Create a css file with src folder](https://xp.io/storage/2vsqrNjd.gif)](https://tailwindcss.com/docs/installation)
7. Go to [tailwindcss.com](https://tailwindcss.com/) and click get started
[![Tailwindcss Website](https://xp.io/storage/2vvt5ATI.gif)](https://tailwindcss.com/)
8. Copy this code and Paste the code in terminal and hit enter and It will install tailwindcss and it will generate the tailwindcss config file
[![Tailwindcss Website - Copy Code](https://xp.io/storage/2vvAykuW.gif)](https://tailwindcss.com/docs/installation)

copy here👇
```bash
# install tailwindcss
$ npm install -D tailwindcss
$ npx tailwindcss init
```
or here👇
```bash
# install tailwindcss
$ npm install -D tailwindcss && npx tailwindcss init
```
9. open tailwind.config.js file and then select all the code and delete all the code and then type `tchtml` this will create tailwindcss config boilerplate
[![Open tailwindcss config file](https://xp.io/storage/2vAwoN1m.gif)](https://tailwindcss.com/docs/installation)
10. Copy this code and Paste the code in terminal and hit enter and It will compile tailwindcss.css file into tailwindcss.dist.css
[![Tailwindcss Website - Copy Code 2](https://xp.io/storage/2x9Wm1cS.gif)](https://tailwindcss.com/docs/installation)

copy here👇
```bash
# compile input.css file into output.css
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
or here👇
```bash
# compile tailwindcss.css file into tailwindcss.dist.css
npx tailwindcss -i ./src/tailwindcss.css -o ./dist/tailwindcss.dist.css --watch
```
11. open index.html file and the type `lt` this will create a link for tailwindcss.dist.css file
[![TailwindCSS link tailwindcss css file Demo](https://xp.io/storage/2xa9mKIo.gif)](https://tailwindcss.com/docs/installation)
12. and try it to write a div tag with class. this will work
[![TailwindCSS Demo](https://xp.io/storage/2BnETKfd.gif)](https://tailwindcss.com/docs/installation)
13. and done, your tailwindcss html setup is working completely
### How to Setup TailwindCSS In React Using TailwindCSS Snippets
1. Open a new terminal and create a react project using create-react-app cli, For Example:
[![Create React App CLI](https://xp.io/storage/6uYOZaN.gif)](https://reactjs.org/docs/create-a-new-react-app.html)
2. Open a react project folder using `code` command in terminal
[![VSCODE CLI - React](https://xp.io/storage/iJ6wja8.gif)](https://code.visualstudio.com/docs/editor/command-line)
3. Open App.js file in src folder. select all the code and delete all the code. and type `rfct` to create react function component boilerplate
[![TailwindCSS react snippets - React](https://xp.io/storage/9Qk2dHJ.gif)](https://xp.io/storage/9Qk2dHJ.gif)
4. Open index.css file in src folder and type `@tb` to create tailwindcss basic boilerplate
[![TailwindCSS basic snippets](https://xp.io/storage/6Ndi0RC.gif)](https://xp.io/storage/6Ndi0RC.gif)
5. Press `` ctrl+` `` to toggle the terminal
[![Toggle terminal - React](https://xp.io/storage/79JjJqo.gif)](https://code.visualstudio.com/docs/terminal/basics)
6. Go to [tailwindcss.com](https://tailwindcss.com/) and click get started. Go to Framework Guides and then select Create React App
[![Tailwindcss Website - React](https://xp.io/storage/7SDRQEM.gif)](https://tailwindcss.com/)
7. Copy this code and Paste the code in terminal and hit enter this will install tailwindcss, postcss and autoprefixer and it will generate both tailwindcss and postcss config file
[![Tailwindcss Website - Copy Code - React](https://xp.io/storage/8qWTs4n.gif)](https://tailwindcss.com/docs/guides/create-react-app)
copy here
```bash
# install tailwindcss and postcss
$ npm install -D tailwindcss postcss autoprefixer
$ npx tailwindcss init -p
```
or here👇
```bash
# install tailwindcss
$ npm install -D tailwindcss postcss autoprefixer && npx tailwindcss init -p
```
8. open tailwind.config.js file and then select all the code and delete all the code and then type `tcreact` to create tailwindcss config boilerplate
[![TailwindCSS Tailwind Javascript Config Snippets - React](https://xp.io/storage/9VFTK4S.gif)](https://tailwindcss.com/docs/guides/create-react-app)
9. and try it to write a class in div tag. this will work
[![TailwindCSS React Demo](https://xp.io/storage/9VIYZIc.gif)](https://xp.io/storage/9VIYZIc.gif)
10. and done, your tailwindcss react setup is working completely

> Note: If you don't have VSCODE Install, You can click this link to download vscode down below👇

VSCODE on Windows:<br>
[Download VSCODE on Windows](https://code.visualstudio.com/docs/?dv=win)<br>
VSCODE on MacOS:<br>
[Download VSCODE on MacOS](https://code.visualstudio.com/docs/?dv=osx)<br>
VSCODE on Linux:<br>
[Download VSCODE on Linux](https://code.visualstudio.com/docs/?dv=linux64_deb)

<!-- For more information About Tailwind CSS Snippets Release<br>
Click link down below<br>
[Tailwind CSS Snippets Release](https://github.com/amiralariska/tailwind-css-snippets-release) -->

**Enjoy**