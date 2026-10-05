---
title: SNS Automation 개인정보처리방침
---

# 개인정보처리방침

적용 대상: SNS Automation · 갱신일: 2026-10-06

## 운영 범위

SNS Automation은 운영자가 소유·관리하는 채널에 사용하는 개인용 도구입니다. 일반 이용자 가입 기능은 없습니다. 공개 안내 페이지에는 별도의 문의 폼, 광고 추적 도구 또는 방문자 분석 스크립트를 설치하지 않습니다. 호스팅 제공자는 서비스 제공을 위해 접속 로그 등을 처리할 수 있습니다.

## 접근하는 정보와 목적

Google OAuth를 통해 승인된 YouTube 채널 ID·채널 이름, 영상 업로드 권한, 업로드한 영상의 ID·주소·공개 범위·처리 상태를 사용합니다. 운영자가 입력한 영상 파일·제목·설명은 업로드에 사용합니다. 접근 토큰과 갱신 토큰은 승인된 API 요청과 연결 유지에 사용합니다. Google 비밀번호는 수집하지 않습니다.

이 정보는 채널 확인, 운영자가 승인한 영상 업로드, 결과 확인 및 중복 방지에 사용합니다. Google 사용자 데이터를 판매하거나 맞춤 광고 또는 범용 AI 모델 학습에 사용하지 않습니다. Google API Services User Data Policy의 제한된 사용 요건에 맞는 용도로만 처리합니다.

## 저장·처리하는 곳

운영용 갱신 토큰과 클라이언트 인증 정보는 GitHub Actions Secrets에 저장하며 실행 중 환경변수로 제공합니다. 비공개 저장소에는 운영 콘텐츠와 게시 결과 기록이 저장될 수 있습니다. Google·YouTube는 인증 및 영상 게시를, GitHub는 저장소·Secrets·실행 환경을 제공합니다. 운영자의 PC에서 콘텐츠 준비와 초기 연결을 수행할 수 있습니다. 공개 안내 문서에는 인증 정보나 비공개 게시 기록을 포함하지 않습니다.

## 보관과 삭제

연결 정보는 운영자가 연결을 유지하는 동안 사용합니다. 게시 ID와 상태 기록은 중복 방지와 운영 기록 확인에 필요한 동안 보관합니다. 현재 모든 기록이 일정 기간 뒤 자동 삭제되는 구조는 아닙니다. 오래된 기록을 별도 파일로 옮기는 작업은 삭제와 다릅니다.

운영자는 Google 계정의 연결 관리 화면에서 앱의 권한을 철회할 수 있습니다. 권한 철회와 GitHub에 저장된 정보의 삭제는 별도 절차입니다. 삭제 요청을 받으면 관련 연결과 자동 실행을 중단하고 해당 Secrets·운영 기록·콘텐츠 및 저장소 이력에 남은 사본의 처리 범위를 확인합니다. 이미 YouTube에 업로드한 영상은 YouTube Studio에서 별도로 관리·삭제할 수 있습니다.

## 문의 및 권한 철회

연결 중단·열람·정정·삭제 요청은 [dddd322014@gmail.com](mailto:dddd322014@gmail.com)으로 문의하세요. 문의할 때 비밀번호나 인증 토큰을 보내지 마세요.

- [Google 계정 연결 관리](https://myaccount.google.com/connections)
- [Google 개인정보처리방침](https://policies.google.com/privacy)
- [YouTube 서비스 약관](https://www.youtube.com/t/terms)
- [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy)
- [GitHub 개인정보처리방침](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

정보 처리 방식이 바뀌면 이 문서와 갱신일을 수정합니다.

[SNS Automation 홈](index.html)
