---
layout: post
title: study  
subtitle: node.js module
tags: [node.js, module]
---

core module 
노드 안에 이미 들어있는 모듈

3rd party module
오픈소스처럼 받아서 사용하는 모듈

# 코어모듈

>const fs = require('fs');
>
>let fileList = fs.readdirSync('.');
>console.log(fileList);
>현재 폴더의 파일의 이름들을 출력-> '.'
>.. -> 이전 폴더 파일 이름 출력 
>
>fs.writeFileSync('new','Hello Node.js!');
>파일 안에 입력하거나 없으면 새로 생성 후 입력

>node package manager
>npm install (서드파티모듈 이름)
>
>package-lock.json이 생기는데 
>그 안에 생기는 dependencies는 주석같이 설명해 주는것이다.
>내가 추가한 서드파티 모듈들이 생긴다.
>서드파티 모듈이 참조한 다른 서드파티 모듈도 생긴다.

