# 카카오 로그인 API 구현 (Node.js)

## ⚠️ 주의 ⚠️

**이 프로젝트는 실제 로그인 용도로 구현되지 않았으므로 신뢰성과 보안을 보장하지 않습니다. 코드를 재사용하지 마세요.**

**실제 프로젝트에 적용하여 발생한 문제에 대해서는 책임을 지지 않습니다.**

## 프로젝트 개요

이 프로젝트는 Node.js를 사용하여 카카오 로그인 API를 구현한 시스템입니다. 사용자가 카카오 계정을 통해 로그인하고 JWT(Json Web Token)를 발급받는 과정을 포함합니다. 로그인 성공 후, 사용자 정보를 MongoDB에 저장하고 클라이언트에 전달하는 기능을 제공합니다.

## 주요 기능

* **카카오 로그인 성공 처리**: 사용자가 카카오 계정으로 로그인에 성공한 후, 인증된 사용자 정보를 처리합니다.
* **JWT 발급 및 쿠키 저장**: 로그인 성공 시 JWT를 발급하고, 이를 쿠키에 저장하여 사용자의 인증 상태를 유지합니다.
* **사용자 정보 MongoDB 저장**: 로그인한 사용자의 정보를 MongoDB 데이터베이스에 저장합니다.
* **클라이언트에 사용자 정보 전달**: 저장된 사용자 정보를 클라이언트에 전달하여, 이후 응용 프로그램에서 활용할 수 있도록 합니다.

## 프로젝트 구조

├── models/        
│   └── (MongoDB 모델 및 JWT 관련 로직)      
├── node_modules/        
├── services/         
│   └── (서비스 관련 로직)         
├── index.js (메인 애플리케이션 파일)         
├── package-lock.json       
└── package.json         

         
## 기술 스택

* Node.js
* MongoDB
* JWT (Json Web Token)
* Kakao Login API

## 설치 및 실행 방법

1.  프로젝트를 클론합니다.
2.  `npm install` 명령어를 실행하여 의존성을 설치합니다.
3.  MongoDB 연결 정보를 설정합니다.
4.  카카오 로그인 API 키를 설정합니다.
5.  `npm start` 명령어를 실행하여 애플리케이션을 실행합니다.

## 추가 정보

* 이 프로젝트는 학습 및 테스트 목적으로 제작되었습니다.
* 실제 서비스에 적용하기 위해서는 추가적인 보안 및 검증 절차가 필요합니다.
* 코드 재사용 시 발생할 수 있는 문제에 대해서는 책임을 지지 않습니다.

## 핵심 사항 요약

* 이 프로젝트는 카카오 로그인 API를 Node.js 환경에서 구현한 것입니다.
* JWT를 사용하여 사용자 인증을 처리하고, MongoDB에 사용자 정보를 저장합니다.
* 보안상의 이유로 실제 서비스에 바로 적용하는 것은 권장되지 않습니다.
