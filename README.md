# inko.js (잉꼬JS)
![inkojs_logo](https://github.com/JonJee/inko/blob/master/images/inkojs_logo.png?raw=true)

[![GitHub license](https://img.shields.io/github/license/jonjee/inko.svg)](https://github.com/jonjee/inko/blob/master/LICENSE)
[![npm](https://img.shields.io/npm/v/inko.svg)](https://npmjs.com/package/inko)
[![jsdelivr](https://data.jsdelivr.com/v1/package/npm/inko/badge)](https://www.jsdelivr.com/package/npm/inko)

## General
- 영어로 쳐야할 글을 한글로 쳤을 때, 혹은 한글로 쳐야할 글을 영어로 쳤을 때 변환해주는 기능을 가진 오픈소스입니다.

## Dependent tools
- [Inko CLI](https://github.com/JonJee/inko-cli) - Use Inko on the command line.

## How to install
```
npm install --save inko
```

## How to use
```
var Inko = require('inko');
var inko = Inko();
```

### 영타 -> 한글
```
inko.en2ko('dkssudgktpdy tptkd!');
// 안녕하세요 세상!
```

### 한타 -> 영문
```
inko.ko2en('ㅗ디ㅣㅐ 재깅!');
// hello world!
```

## TODO LIST
[x] develop @types/inko module for typescript
[x] add gulp file to minify inko.js or do something
[x] launch inkojs official introduction website
[x] improve inkojs logo

## How To Contribute
이 오픈소스 프로젝트에 누구나 기여할 수 있습니다. 기여하고 싶은 분들은 이 레포지토리를 포크한 후 풀리퀘스트 요청해주세요!

## License
MIT