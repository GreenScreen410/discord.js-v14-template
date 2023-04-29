# discord.js-v14-template
![node-current](https://img.shields.io/node/v/discord.js?style=flat-square)
![license](https://img.shields.io/github/license/GreenScreen410/discord.js-v14-template?style=flat-square)

## English

This code was from reconlx's [djs-base-handler](https://github.com/reconlx/djs-base-handler), then modified according to the discord.js v14 and removed text commands.

**commands** - This folder contains commands.<br/>
**event** - This folder contains files related to discord.js events. (Like "ready", "interactionCreate")<br/>
**handler**  - This folder contains files read files from the command folder.<br/>
**index.js** - This is the main file to run the bot.<br/>
**package-lock.json** - This is a file related to the npm package.<br/>
**package.json** - This is a file related to the npm package.

1 First, type `npm install` in your console.<br/>
2 You need to make .env file. This process is very important and this file will serve to store the bot's tokens. Type this in your .env file `TOKEN = token` <br/>
**YOU NEED TO CHANGE token TO YOUR BOT'S TOKEN.**</br>
4 Go to handler > index.js and change "825741743235268639" to your bot testing server ID.</br>
You don't have to worry that the command will be registered on all servers to which the bot is connected in a few hours.</br>
5 Type `node .` or `node index.js` in your console.

You can check installed modules by `npm ls`.

<br/>

## 한국어
이 코드는 reconlx님의 [djs-base-handler](https://github.com/reconlx/djs-base-handler)에서 따왔습니다. discord.js v14에 맞게 몇몇 코드를 수정했고, 텍스트 명령어를 제거하였습니다.

**commands** - 명령어 파일들이 들어있는 폴더입니다.<br/>
**event** - discord.js 이벤트가 발생했을 때, 실행시키는 파일이 들어있는 폴더입니다. ("ready", "interactionCreate" 등...)<br/>
**handler**  - commands 폴더에 있는 명령어 파일들을 불러오는 파일이 있는 폴더입니다.<br/>
**index.js** - 봇을 실행시킬 때 쓰이는 메인 파일입니다. <br/>
**package-lock.json** - npm 패키지 관련 파일입니다.<br/>
**package.json** - npm 패키지 관련 파일입니다.

1 먼저 콘솔에 `npm install`을 입력해 주세요.<br/>
2 .env 파일을 만들어야 합니다. 이 과정은 매우 중요하며, 봇의 토큰을 저장하는 역할을 할것입니다. .env 파일에 이렇게 써주세요. `TOKEN = token` <br/>
**token을 자신의 봇 토큰으로 바꾸는 것 잊지 마세요!**<br/>
4 handler 폴더 내 index.js에서 "825741743235268639"를 자신의 봇 테스트용 서버 ID로 바꿔주세요.
몇 시간 내로 봇이 접속해 있는 모든 서버에 명령어가 등록될 것이므로 걱정하지 않으셔도 됩니다.</br>
5 `node .` 아니면 `node index.js` 를 콘솔에 입력해 주세요. </br>

설치된 모듈은 `npm ls` 명령어를 통해 확인하실 수 있습니다.
