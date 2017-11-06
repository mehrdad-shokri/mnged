<h1 align="center">MNGED</h1>

<div align="center">
  <strong>MNGED is a PWA which helps you to keep track of your study life 🎓</strong>
</div>
<div align="center">
  ⚠ Attention: MNGED is not finished yet and there're many bugs present! ⚠
</div>

<br />

<div align="center">
  <sub>&lt; /&gt; with ❤︎ by <a href="https://github.com/m4r1vs">Marius Niveri</a>
</div>

## Getting started
To try it on your own run the following commands after you installed [yarn](https://yarnpkg.com/lang/en/):
```sh
yarn
yarn start
```
If you don't have [yarn](https://yarnpkg.com/lang/en/) installed, go ahead and do it. It's definitely worth it ;)
If you have [nvm](https://github.com/creationix/nvm), you also should run `nvm use v8` to use node version 8.X.X
## About
MNGED is a so called Progressive Web App (PWA). PWA's stand out because they are fast and always work, even with no connection to the internet.
![Screenshot of the dashboard on iMac](https://raw.githubusercontent.com/m4r1vs/mnged/master/src/assets/imgs/mnged_dashboard_screenshot_big.png)
MNGED uses [Firebase](https://firebase.google.com) for authentication and as a database. Firesbase is developed and maintained by Google. The authentication is build by the same team that also build Google Sign In and is responsible for other security at Google. But that also means that Google has access to our database which you may or may not care about.
![Screenshot of a detailed view of class on Samsung S7](https://raw.githubusercontent.com/m4r1vs/mnged/master/src/assets/imgs/mnged_class_screenshot.png)
As the UI provider I decided to go with Preact, a lightweight 3kb fork of React. For storing the state I use MobX, it's a simple but powerful state management solution. And finally as the database I went with Firebase, a mostly free hosting and database provided by Google. The nice thing about firebase is that it comes with a nice JavaScript library which enables Authentication and live-updates when the database changes.
![Screenshot of the dashboard on Samsung S7](https://raw.githubusercontent.com/m4r1vs/mnged/master/src/assets/imgs/mnged_dashboard_screenshot.png)
## Contributers
Huge thanks to [Jason Miller](https://github.com/developit/) for building Preact and the Preact CLI. And also thanks to him for helping this projects to gain some popularity with his [Twitter Quote](https://twitter.com/_developit/status/923555370219470848)!