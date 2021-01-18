# 코르도바, 아이오닉 세팅
코르도바와 아이오닉을 이용한 프레임워크 세팅

### 코르도바가 무어야?
- HTML, CSS 및 JS가 포함 된 모바일 앱 그리고 단일 코드 기반의 멀티플 플랫폼을 타겟으로 한 무료이자 오픈소스 프레임워크
> 자바스크립트 자체가 웹표준을 따르고 있어 다양한 플랫폼 장치의 기능에 접근 할 수 있는 기본 컨테이너에 HTML / 자바스크립트(JavaScript) 앱을 포장(Wrapping)하고 별도로 코드를 수정하는 번거로운 작업 없이도 사용 가능한 앱을 개발할 수 있어요

- 코르도바에서 제공하는 플러그인들과 플러그인 개발가이드를 통한 새로운 플로그인으로 인해 하이브리드 앱 개발의 단점을 최소로 줄여줍니다

- 다양한 언어 지원
> **Adobe Phonegap** : 대표적인 모바일 개발 프레임워크로서 HTML5, CSS, JavaScript를 활용해 모바일 기기를 위한 애플리케이션을 제작
> **Ionic / Onsen UI** : 앵귤러(Angular JS) 를 이용한 개발.
> **Visual Studio** : Android, iOS 및 Windows 용 크로스 플랫폼 앱을 제작하는 데 굉장한 인기가 있고 고급 빌드 및 디버깅 지원으로 완성


### 개발환경
- OS : Windows 10
- powershell
- Git : git version 2.19.1.windows.1
- Visual Studio Code
- NodeJs : v10.15.3
- npm : 6.4.1


### 설치
```
npm install -g ionic cordova
```

### 앱 생성
```
ionic start {project-name} tabs
```
-  angular JS 선택
- ionic .. new account -> Y

```
cd {project-name}
```
### 아이오닉 실행 
```
ionic serve
```
- port 8100 
- 

### VS code 실행
- **e2e(exchange-to-exchange)** :  ionic이 지원하는 여러 환경으로 변환하기 위한 폴더.
- **node_modules** : npm module 의 폴더
- **src** : 주된 관심사로 ionic 작업을 위한 소스가 Angular 구조로 삽입되어 있는 디렉터리입니다.
- **그외** : .gitignore 및 angular.json, package.json등 config관련된 파일들 목록입니다. 


### ionic lab 실행하기

```
ionic serve --lab
```
- install ionic-lab -> Y
- `ionic integrations disable capacitor`-> cordova 를 이용하기 위해 삭제(충돌남)

```
ionic  cordova platform add ios
ionic cordova platform add android	
```
