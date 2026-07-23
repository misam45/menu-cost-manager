# Menu Profitability MVP

메뉴별 원가, 원가율, 권장 판매가를 관리하는 정적 웹앱입니다.

## 포함 기능

- 대시보드
- 원재료 리스트 및 등록·편집·삭제
- 메뉴 리스트 및 등록·편집·삭제
- 레시피 기반 자동 원가 계산
- 목표 원가율 기반 권장 판매가 계산
- 적정·주의·위험 상태 구분
- 메뉴별 원가 현황 및 위험 메뉴 분석
- 브라우저 LocalStorage 저장
- 반응형 화면

## 프로젝트 구조

```text
menu-profitability-app/
├─ index.html
├─ README.md
├─ vercel.json
└─ .gitignore
```

## GitHub 업로드

1. GitHub에서 새 Repository를 생성합니다.
2. ZIP 압축을 풉니다.
3. 폴더 안의 파일 전체를 Repository 루트에 업로드합니다.
4. `Commit changes`를 누릅니다.

## Vercel 배포

1. Vercel에서 `Add New` → `Project`를 선택합니다.
2. GitHub의 Repository를 연결합니다.
3. Framework Preset은 `Other`를 선택합니다.
4. Build Command와 Output Directory는 비워둡니다.
5. Deploy를 누릅니다.

## 데이터 저장 방식

현재 버전은 서버와 데이터베이스가 없는 MVP입니다. 사용자가 등록한 데이터는 해당 브라우저의 LocalStorage에 저장됩니다. 다른 기기나 브라우저와 데이터가 공유되지는 않습니다.
