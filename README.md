# BangBa 방탈출 매니아들의 바다

## 개요

방탈출 카페를 자주 가는 사람들이 방탈출 카페를 검색하려면 일일히 검색하거나 인터넷 카페를 통해 찾을수 밖에 없습니다. 그런 사람들을 위해 난이도별, 테마별로 찾아주는 홈페이지를 만들기로 했습니다.

## 시작하기에 앞서

방탈출 카페 관련 api가 없기 때문에 방탈출 데이터를 모으는 방법을 방탈출 카페 크롤링, 사용자들이 직접 카페 등록하기 등의 방법을 생각했습니다. 백엔드 지식을 가지고 있지 않기 때문에 방탈출 카페를 등록하는 방식을 채택했습니다. 후에 백엔드를 익히게 된다면 크롤링이나 직접 api를 만들어 배포하는 방법도 구현하겠습니다.

## 기능

### 방탈출 카페 찾기 기능

- 방탈출 카페 등록 방탈출의 사진, 난이도, 테마 등을 설정해 등록할 수 있음
- 방탈출 카페 검색하기 등록된 방탈출을 난이도별, 테마별로 검색할 수 있음
- 방탈출 카페 추천, 댓글쓰기 방탈출 추천과 댓글로 사용자의 후기를 알 수 있게 함

### 유저 관련 기능

- 유저 회원가입, 로그인 간단한 양식을 통한 유저 회원가입, 로그인 기능
- 소셜 로그인 일반적인 로그인 말고도 카카오, 구글, 네이버 로그인을 통해 매우 간단하게 회원가입을 할 수 있음
- 관심있는 방탈출 카페 등록 자주 가거나 관심있는 방탈출 카페를 등록해 쉽게 접근할 수 있음

### 방탈출 카페 지도 기능

- 지도 api를 이용하여 방탈출 카페의 위치를 쉽게 찾을 수 있도록 하는 기능
