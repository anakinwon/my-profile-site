# 프로젝트 내의 규칙을 정의하는 파일. (500 줄 이하 권장))

# 내 개발 환경
- OS: Windows 11

# 프로젝트 개요
React + TypeScript 기반 할일 관리 앱

# 기술 스택
- React 19 + TypeScript
- Tailwind CSS
- Zustand (상태관리)

# 빌드 & 실행 명령어
- 개발 서버: npm run dev
- 빌드: npm run build
- 테스트: npm run test

# 코드 컨벤션
- 컴포넌트 파일명: PascalCase (예: TodoList.tsx)
- 훅 파일명: use로 시작 (예: useTodos.ts)
- 타입 정의는 types/ 디렉토리에 모아서 관리

# 프로젝트 구조
- src/components/ : UI 컴포넌트
- src/hooks/ : 커스텀 훅
- src/types/ : TypeScript 타입 정의
- src/stores/ : Zustand 스토어

## 언어 및 커뮤니케이션 규칙
- **기본 응답 언어**: 한국어
- **코드 주석**: 한국어로 작성
- **커밋 메시지**: 한국어로 작성
- **문서화**: 한국어로 작성
- **변수명/함수명**: 영어 (코드 표준 준수)


# 개인 선호도
- @~/.claude/my-project-instructions.md

# 작업 방식
- 파일 수정 전 변경 계획을 먼저 설명
- 한 번에 너무 많은 파일을 수정하지 말 것.

# 작업 디렉토리
your-project/
├── .claude/
│   ├── CLAUDE.md           # 주 프로젝트 지침
│   └── rules/
│       ├── code-style.md   # 코드 스타일 가이드라인
│       ├── testing.md      # 테스트 규칙
│       └── security.md     # 보안 요구사항



---
paths:
  - "src/**/*.{ts,tsx}"
  - "lib/**/*.ts"
  - "tests/**/*.test.ts"
---