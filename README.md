<div align="center">
<!-- <img src="public/icon-128.png" alt="logo"/> -->
<h1> Silent Focus </h1>

![GitHub action badge](https://github.com/bambooom/silent-focus/actions/workflows/build.yml/badge.svg)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbambooom%2Fsilent-focus&count_bg=%23E7B3EB&title_bg=%23555555&icon=&icon_color=%23EDCFEF&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)

</div>

## Intro <a name="intro"></a>

A chrome extension to get focus and block distracting websites.

## Features <a name="features"></a>

- [React 18](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Vite](https://vitejs.dev/)
- [SASS](https://sass-lang.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Chrome Extension Manifest Version 3](https://developer.chrome.com/docs/extensions/mv3/intro/)

## Installation <a name="installation"></a>

### Procedures <a name="procedures"></a>

1. Clone this repository.
2. Change `name` and `description` in package.json => **Auto synchronize with manifest**
3. Run `yarn` or `npm i` (check your node version >= 16)
4. Run `yarn dev` or `npm run dev`
5. Load Extension on Chrome
   1. Open - Chrome browser
   2. Access - chrome://extensions
   3. Check - Developer mode
   4. Find - Load unpacked extension
   5. Select - `dist` folder in this project (after dev or build)
6. If you want to build in production, Just run `yarn build` or `npm run build`.

## Screenshots <a name="screenshots"></a>

### New Tab <a name="newtab"></a>

<img width="971" alt="스크린샷 2022-04-11 오전 2 22 00" src="https://user-images.githubusercontent.com/53500778/162631646-cd40976b-b737-43d0-8e6a-6ac090a2e2d4.png">

### Popup <a name="popup"></a>

<img width="305" alt="스크린샷 2022-04-11 오전 2 22 11" src="https://user-images.githubusercontent.com/53500778/162631660-d35c5f12-e0d7-4431-a020-97024cdda7a7.png">

## Documents <a name="documents"></a>

- [Vite Plugin](https://vitejs.dev/guide/api-plugin.html)
- [ChromeExtension](https://developer.chrome.com/docs/extensions/mv3/)
- [Rollup](https://rollupjs.org/guide/en/)
- [Rollup-plugin-chrome-extension](https://www.extend-chrome.dev/rollup-plugin)
