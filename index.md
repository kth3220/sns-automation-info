---
title: SNS Automation
---

# SNS Automation

**채널 소유자가 자신의 콘텐츠를 준비하고 게시 결과를 확인하는 개인용 운영 도구입니다.**

이 도구는 운영자가 직접 관리하는 YouTube 채널을 Google OAuth로 연결합니다. 운영자가 준비한 영상과 제목·설명을 업로드하고, 올바른 채널에 업로드되었는지와 영상 처리 상태를 확인합니다. 일반 이용자의 회원가입이나 다른 사람의 채널을 대신 운영하는 서비스는 제공하지 않습니다.

## 연결과 게시 과정

1. 운영자가 Google 로그인 화면에서 사용할 채널과 권한을 확인합니다.
2. 프로그램이 지정한 채널 ID와 Google에서 확인한 채널을 비교합니다.
3. 승인된 콘텐츠만 게시 후보로 준비합니다. 현재 초기 연결 검증은 비공개 시험 영상으로 진행합니다.
4. 영상 ID와 처리 상태를 기록해 중복 업로드를 방지합니다.

## 사용하는 Google 권한

- **YouTube 업로드 (`youtube.upload`)**: 운영자가 승인한 영상 업로드.
- **YouTube 읽기 (`youtube.readonly`)**: 연결된 채널 식별과 업로드 결과 확인.

비밀번호를 직접 수집하지 않습니다. Google 로그인은 Google의 공식 인증 화면에서 진행합니다. 이 도구는 Google 또는 YouTube가 제공하거나 보증하는 서비스가 아닙니다. YouTube API Services를 이용하며, 별도의 공개 업로드 승인이 필요한 경우 해당 절차를 따릅니다.

## 안내 문서

- [개인정보처리방침](privacy.html)
- [이용 안내 및 약관](terms.html)
- [Google 계정 연결 관리·철회](https://myaccount.google.com/connections)

지원 문의: [dddd322014@gmail.com](mailto:dddd322014@gmail.com)

최종 갱신: 2026-10-06
