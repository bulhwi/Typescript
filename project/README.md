## 코로나 세계 현황판 만들기

최종 프로젝트 폴더입니다

## 자바스크립트 프로젝트에 타입스크립트 적용하기
1. 타입스크립트 기본환경 구성
    - [X] npm 초기화    
    - [X] 타입스크립트 라이브러리 설치    
    - [X] 타입스크립트 설정 파일 생성 및 기본 값 추가  
    - [X] 자바스크립트 파일을 타입스크립트 파일로 변환하기  
    - [X] 'tsc' 명령어로 타입스크립트 변환  
2. 명시적인 `any` 선언하기
   - `tsconfig.json` 파일에 `noImplicitAny` 값을 `true`로 추가
   - 가능한한 구체적인 타입으로 타입 정의
3. 프로젝트 환경구성
   - babel, eslint, prettier등의 환경 설정.
4. 외부 라이브러리 모듈화
```
   npm init -y
   npm i -D typescript @babel/core @babel/preset-env @babel/preset-typescript @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint prettier eslint-plugin-prettier
```
바벨, 타입스크립트 및 문법검사(eslint), 코드정리도구(prettier) 라이브러리 추가


## 참고 자료

- [존스 홉킨스 코로나 현황](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
- [Postman API](https://documenter.getpostman.com/view/10808728/SzS8rjbc?version=latest#27454960-ea1c-4b91-a0b6-0468bb4e6712)
- [Type Vue without Typescript](https://blog.usejournal.com/type-vue-without-typescript-b2b49210f0b)
- [tslint를 사용하지 않고 eslint를 사용하는 이유](https://github.com/microsoft/typescript/issues/29288)

   