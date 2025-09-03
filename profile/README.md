<!-- PROJECT LOGO -->
<div align="center">
  <h1>NEW 하루의끝</h1>
</div>

<!-- TABLE OF CONTENTS -->
<details align="right">
  <summary>Table of Contents</summary>
    <div><a href="#프로젝트-소개">프로젝트 소개</a></div>
    <div><a href="#서비스 주요 기능">서비스 주요 기능</a></div>
    <div><a href="#멤버-소개">멤버 소개</a></div>
    <div><a href="#기술-스택">기술 스택</a></div>
</details>


## 프로젝트 소개

### 서비스 이름 : 🌃 하루의 끝 (Haru2End) 🌃

> 하루를 끝내며 오늘의 순간과 감정을 기록하고, 감성적인 일기를 꾸밀 수 있는 다이어리형 서비스

- **부제**: 하루의 마무리를 기록하는 감성 일기 플랫폼

- **타겟층**: 하루가 끝나기 전 일기를 쓰는 분, 새벽 감성을 좋아하는 분

<br/>

## 서비스 주요 기능

### 1) 기록 경험 최적화
- **빠른 일기 작성 에디터**: 제목·본문·태그를 간결하게 입력하고, 작성 흐름을 끊지 않도록 핵심 입력만 노출합니다.
- **자동 임시저장(Local Storage)**: 작성 중 새로고침·창 닫힘에도 내용이 보존되어 초안 유실을 최소화합니다.
- **감정 선택(무드 픽커)**: 하루의 분위기를 아이콘으로 표시하여 나중에 감정 흐름을 쉽게 회고할 수 있습니다.
- **이미지 첨부·미리보기**: 단일 이미지를 추가하고, 업로드 전 썸네일로 확인합니다.

### 2) 정리·탐색
- **카테고리/태그 기반 분류**: 주제·테마별로 일기를 묶어 보고 필터링할 수 있습니다.
- **정렬·페이지네이션**: 최신순, 인기순 등으로 정렬하고, 페이지 단위로 효율적으로 탐색합니다.

### 3) 공유와 상호작용(커뮤니티)
- **피드 노출(공개 선택 시)**: 공개로 작성한 일기는 피드에 노출되어 다른 사용자가 읽을 수 있습니다.
- **좋아요/북마크**: 공감은 좋아요로, 다시 보고 싶은 글은 북마크로 관리합니다.
- **댓글/대댓글**: 글 아래에서 대화를 이어가며 공감과 피드백을 주고받습니다.
- **링크 공유**: 외부로 손쉽게 공유할 수 있는 퍼머링크를 제공합니다.

### 4) 안전·신뢰
- **신고/차단**: 부적절한 글·댓글·사용자를 신고하거나 노출을 차단할 수 있습니다.
- **가이드라인/모더레이션**: 커뮤니티 정책에 따라 위반 콘텐츠를 선제적으로 처리합니다.

### 5) 개인화·접근성
- **다크/라이트 모드**: 눈의 피로를 줄이고 환경에 맞춰 가시성을 높입니다.
- **다국어 지원(i18n)**: 한국어를 기본으로 다양한 언어 확장이 가능합니다.
- **시간대/날짜 현지화**: 사용자의 로캘과 시간대에 맞춰 날짜·시간을 표시합니다.
- **모바일 최적화**: 작은 화면에서도 입력·탐색·상호작용이 막힘없이 동작하도록 UI를 구성합니다.

### 6) 계정·보안
- **이메일 기반 인증(JWT)**: 안전한 세션 관리로 로그인 상태를 유지합니다.
- **프로필 관리**: 닉네임·이미지·소개 등 사용자 정보를 편집할 수 있습니다.
- **프라이버시 옵션**: 글 단위로 공개/비공개를 선택하고, 필요한 경우 익명 게시를 지원합니다.

### 7) 성능·운영(서비스 관점)
- **정적 자산 캐싱·버전관리**: 새 버전 배포 시에도 깨진 리소스 없이 안정적으로 로딩됩니다.
- **경량 UI 컴포넌트**: Tailwind/shadcn 기반의 최소 런타임 오버헤드로 빠른 초기 렌더링을 제공합니다.
- **모듈형 구조**: 프론트엔드·서버·모바일(React Native)이 느슨하게 결합되어 독립 배포가 가능합니다.

> 요약: “쓰는 경험은 가볍게, 정리와 탐색은 쉽게, 소통은 안전하게.”  
> 하루의 끝은 하루를 정리하는 일기 작성부터, 다시 찾고 공유하는 과정까지 전 흐름을 단순하고 안정적으로 제공합니다.

<br/>

## 멤버 소개

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/beargame123">
        <img src="https://avatars.githubusercontent.com/u/81502235" width="100px;" alt="" /><br />
        <sub>
          <b>김호영</b><br />
          <b>백엔드, 프론트엔드, android + ios</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<br/>


## 기술 스택

### [FRONTEND](https://github.com/KR-TD/td-front)

- 핵심 기술: Next.js, React, TypeScript
- 스타일링처리: Tailwind CSS, shadcn/ui
- 폼 처리: React Hook Form, Zod
- 번역: i18next
- 패키지 매니저: pnpm

### [BACKEND](https://github.com/KR-TD/td-server)

- Kotlin, Spring Boot, JPA, Spring Security, JWT, QueryDsl
- MySQL, Redis
- MiniPc (Server)
- SMTP

### [Phone](https://github.com/KR-TD/td-phone)

- Core & Language: React, React Native, TypeScript, JavaScript (ES6+)
- Key Libraries: react-native-safe-area-context (노치/동적섬 대응), react-native-webview (웹 콘텐츠 표시)
- Platforms & Build: iOS (CocoaPods), Android (Gradle), Node.js (npm)
