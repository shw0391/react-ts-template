# React + TypeScript 실습 템플릿

수업 자료(리액트 프로젝트 생성)의 설정이 모두 적용된 Vite 프로젝트입니다.

- React 19 + Vite 8 + TypeScript 5.9.3 (ESLint 호환 버전)
- ESLint + typescript-eslint + React Hooks / React Refresh 플러그인
- concurrently, tsx 설치 설정 완료
- `tsconfig.app.json`, `tsconfig.node.json`에 `strict: true`, `DOM.Iterable` 적용
- `.vscode/settings.json` (ESLint, Code Runner, Prettier, TypeScript 버전 설정)
- `.vscode/extensions.json` (ESLint, Prettier, Code Runner 확장 추천)

## 새 프로젝트 만들기

```bash
npx degit <GitHub아이디>/react-ts-template todo-app
cd todo-app
npm install
npm run dev
```

`todo-app` 자리에 원하는 프로젝트 폴더 이름을 넣으면 됩니다.

GitHub 저장소 페이지에서 **Use this template** 버튼을 눌러 새 저장소로 만들어도 됩니다.

## 명령어

| 명령어 | 기능 |
|---|---|
| `npm run dev` | 개발 서버 + 브라우저 자동 실행 + 실시간 타입 검사 |
| `npm run lint` | ESLint 코드 검사 |
| `npm run build` | 타입 검사 후 배포용 빌드 |
| `npm run preview` | 빌드 결과 미리보기 |
