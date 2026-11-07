# Phoenix Player

**Windows용 무료 영상 플레이어 겸 영상 관리 프로그램**

보는 일부터 찾고 정리하는 일까지 한 프로그램에서 끝납니다. 광고가 없고, 인터넷으로 아무것도 보내지 않습니다.

## ⬇️ 다운로드

**[최신 버전 받기 → Releases](https://github.com/NovacoreWorks/PhoenixPlayer-Release/releases/latest)**

1. `PhoenixPlayer-버전.zip`을 받습니다.
2. 원하는 곳에 압축을 풉니다. 설치 과정은 없습니다.
3. `PhoenixPlayer\PhoenixPlayer.exe`를 실행합니다.

> 처음 실행할 때 Windows가 "PC 보호" 창을 띄우면 **추가 정보 → 실행**을 누르세요.
> 코드 서명 인증서를 쓰지 않는 무료 프로그램이라 나오는 안내입니다.

**필요 환경**: Windows 10 (2004 이상) / Windows 11, 64비트. .NET이나 코덱을 따로 설치할 필요가 없습니다.

## ✅ 공식 배포처는 이곳 하나뿐입니다

Phoenix Player는 **이 페이지에서만 배포합니다.** 블로그, 카페, 자료실 등 다른 곳에 올라온 파일은 공식 배포본이 아니며, 누군가 고친 파일일 수 있습니다.

### 정품 확인 방법
- **자동**: 프로그램이 실행될 때 파일이 공식 배포본과 같은지 스스로 검사합니다. 다르면 경고가 나옵니다 (이 PC 안에서만 검사하고, 인터넷 연결은 하지 않음).
- **직접**: 받은 zip의 SHA-256 값을 각 버전 안내에 적힌 값과 비교합니다. PowerShell에서 아래처럼 입력합니다.
  ```powershell
  Get-FileHash .\PhoenixPlayer-1.0.0.zip -Algorithm SHA256
  ```

## 주요 기능

- **강력한 재생**: VLC 엔진 내장 (MP4 · MKV · AVI · WMV · TS · MOV · WebM 등), 하드웨어 가속, 이어 보기, 배속, 구간 반복
- **자체 탐색기**: 영상 폴더 여러 개 등록 (NAS · 외장 하드 포함), 새 파일 자동 표시, 큰 카드 · 바둑판 · 포스터 · 리스트 · 표 보기
- **장르 · 연도 · 시리즈**: 파일 이름의 연도를 자동으로 읽고, 시리즈를 순서대로 정리
- **내 취향대로 정리**: 별점 · 태그 · 메모 · 배우 · 포스터. 원본 파일은 건드리지 않음
- **장면 즐겨찾기**: `B` 한 번으로 장면 저장, 구간 반복
- **찾기와 필터**: `★4` `#태그` `@배우` 같은 짧은 검색어, 조건 겹쳐 고르기
- **한국어 자막**: SMI · SRT · ASS · VTT, 글자 형식 자동 판별로 깨짐 방지
- **도구**: 캡처, 장면 탐색 격자, GIF 만들기, 중복 영상 찾기, 일괄 이름 바꾸기

## 사용 조건 (요약)

- 개인 · 가정 · 회사 어디서든 **무료**로 쓸 수 있습니다.
- 받은 그대로라면 다른 사람에게 나눠 줘도 됩니다. **판매, 수정 후 배포, 만든이 표시 삭제는 금지**합니다.
- 프로그램은 "있는 그대로" 제공됩니다. 사용 중 생긴 손해에 대해 만든이는 책임지지 않습니다.
- 전체 내용은 압축 파일 안의 `사용조건.txt`를 보세요.

## 오픈소스

VLC / libVLC (LGPL 2.1+), LibVLCSharp (LGPL 2.1+), FFmpeg (GPL 3), .NET (MIT), Microsoft.Data.Sqlite (MIT), SQLite (Public Domain), VirtualizingWrapPanel (MIT)를 사용합니다.
저작권, 라이선스, 소스 받을 곳은 압축 파일 안의 `오픈소스 고지.txt`와 `licenses` 폴더에 있습니다.

## 문의

- 만든이: **NovacoreWorks(LJY)**
- 이메일: **novacoreworks@gmail.com**
- 오류 제보와 문의는 [Issues](https://github.com/NovacoreWorks/PhoenixPlayer-Release/issues)나 이메일로 보내 주세요.

---

Copyright © 2026 NovacoreWorks(LJY). All rights reserved.
이 저장소에는 배포 파일만 올립니다. 프로그램 소스 코드는 공개하지 않습니다.
