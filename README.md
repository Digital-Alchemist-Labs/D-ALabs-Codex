# D-ALabs Codex

현대적인 웹 개발을 위한 종합 가이드와 베스트 프랙티스 문서입니다.

[![Mintlify](https://img.shields.io/badge/Powered%20by-Mintlify-6366F1)](https://mintlify.com)

## 📚 콘텐츠

- **Next.js** - React 기반 풀스택 프레임워크 가이드
- **TypeScript** - 타입 안전한 JavaScript 개발
- **API 설계** - RESTful API 설계 원칙과 베스트 프랙티스

## 🚀 로컬 개발

### 필수 요구사항

- [Node.js](https://nodejs.org/) 20.17.0 이상 (LTS 버전 권장)

### 설치

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm run dev
```

개발 서버가 실행되면 `http://localhost:3000`에서 문서를 확인할 수 있습니다.

### 사용 가능한 명령어

| 명령어                 | 설명           |
| ---------------------- | -------------- |
| `npm run dev`          | 개발 서버 실행 |
| `npm run build`        | 프로덕션 빌드  |
| `npm run broken-links` | 깨진 링크 검사 |

## 📁 프로젝트 구조

```
D-ALabs-Codex/
├── docs.json           # Mintlify 설정 파일
├── introduction.mdx    # 소개 페이지
├── nextjs/            # Next.js 문서
│   ├── introduction.mdx
│   ├── installation.mdx
│   ├── quick-start.mdx
│   ├── routing.mdx
│   └── data-fetching.mdx
├── typescript/        # TypeScript 문서
│   ├── introduction.mdx
│   ├── basic-types.mdx
│   └── best-practices.mdx
├── api-design/        # API 설계 문서
│   ├── introduction.mdx
│   └── rest-principles.mdx
├── logo/             # 로고 파일
├── images/           # 이미지 파일
└── favicon.svg       # 파비콘
```

## ✍️ 문서 작성

### 새 페이지 추가

1. 적절한 폴더에 `.mdx` 파일 생성
2. frontmatter 추가:

```mdx
---
title: "페이지 제목"
description: "페이지 설명"
icon: "아이콘 이름"
---

# 제목

콘텐츠...
```

3. `docs.json`의 `navigation`에 페이지 경로 추가

### Mintlify 컴포넌트

Mintlify는 다양한 내장 컴포넌트를 제공합니다:

- `<Card>` - 링크 카드
- `<CardGroup>` - 카드 그룹
- `<Accordion>` - 접을 수 있는 섹션
- `<Tabs>` / `<Tab>` - 탭 콘텐츠
- `<Steps>` / `<Step>` - 단계별 가이드
- `<CodeGroup>` - 코드 블록 그룹
- `<Note>`, `<Warning>`, `<Info>`, `<Tip>`, `<Check>` - 콜아웃

[Mintlify 컴포넌트 문서](https://mintlify.com/docs/content/components)에서 더 자세한 내용을 확인하세요.

## 🤝 기여

문서에 대한 피드백이나 개선 제안은 언제든 환영합니다!

1. 이 저장소를 Fork하세요
2. 새 브랜치를 생성하세요 (`git checkout -b feature/improvement`)
3. 변경사항을 커밋하세요 (`git commit -am 'Add some improvement'`)
4. 브랜치에 Push하세요 (`git push origin feature/improvement`)
5. Pull Request를 생성하세요

## 📄 라이선스

이 프로젝트는 [MIT 라이선스](LICENSE)를 따릅니다.

## 🔗 링크

- [D-ALabs GitHub](https://github.com/D-ALabs)
- [Mintlify 문서](https://mintlify.com/docs)
