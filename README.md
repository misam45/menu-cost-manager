# 메뉴 원가 계산기 MVP

재료의 매입 단가와 메뉴별 사용량을 바탕으로 다음 항목을 계산하는 정적 웹페이지입니다.

- 메뉴별 재료 수
- 메뉴 원가
- 현재 원가율
- 목표 원가율 기준 권장 판매가

## 실행 방법

별도의 설치 과정이 없습니다.

1. `index.html` 파일을 브라우저에서 엽니다.
2. 또는 GitHub 저장소에 전체 파일을 업로드한 뒤 Vercel에서 배포합니다.

## GitHub 업로드

1. GitHub에서 새 Repository를 생성합니다.
2. 이 폴더 안의 파일을 모두 업로드합니다.
3. Commit changes를 선택합니다.

## Vercel 배포

1. Vercel에 로그인합니다.
2. `Add New` → `Project`를 선택합니다.
3. GitHub 저장소를 연결합니다.
4. Framework Preset은 `Other`로 둡니다.
5. 별도의 Build Command와 Output Directory를 입력하지 않고 Deploy를 선택합니다.

## 프로젝트 구조

```text
menu-cost-mvp-vercel/
├─ index.html
├─ README.md
└─ vercel.json
```

## 현재 MVP 범위

- 데이터는 브라우저 메모리에서만 관리됩니다.
- 페이지를 새로고침하면 초기 샘플 데이터로 돌아갑니다.
- 로그인, 데이터베이스, 사용자별 저장 기능은 포함되어 있지 않습니다.
