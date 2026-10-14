# 🍸 Cock-tail

칵테일 API를 활용해 다양한 칵테일을 둘러보고, 검색하고, 마음에 드는 칵테일을 저장할 수 있는 웹 애플리케이션입니다.

🔗 배포 주소: https://cocktail-rang2.netlify.app/

## 주요 기능

- **칵테일 검색**: 이름으로 칵테일을 검색합니다.
- **재료 기반 필터링**: 선택한 재료가 들어간 칵테일만 모아서 봅니다.
- **무한 스크롤**: 스크롤하면 칵테일 목록이 이어서 로드됩니다.
- **북마크**: 마음에 드는 칵테일을 저장하고 북마크 목록에서 다시 확인합니다.
- **뷰 전환 및 네비게이션**: 페이지 간 이동과 목록/북마크 화면 전환을 지원합니다.
- **다크 모드**: 라이트/다크 테마를 전환할 수 있습니다.

## 기술 스택

| 구분 | 사용 기술 |
| Framework | React |
| Build Tool | Vite |
| 서버 상태 관리 | TanStack React Query |
| HTTP Client | Axios |
| Styling | Tailwind CSS |
| 데이터 | TheCocktailDB API |

## 시작하기

### 설치 및 실행

```bash
# 저장소 클론
git clone https://github.com/Rang97/Cock-tail_project.git
cd Cock-tail_project

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev
```

브라우저에서 터미널에 표시된 주소(기본 `http://localhost:5173`)로 접속합니다.

## 프로젝트 구조

```
Cock-tail_project/
├── src/
│   ├── assets/          # 이미지 등 정적 리소스
│   ├── components/      # UI 컴포넌트
│   ├── App.jsx          # 루트 컴포넌트
│   ├── index.css        # 전역 스타일 (Tailwind)
│   └── main.jsx         # 진입점
├── index.html
├── vite.config.js
├── eslint.config.js
└── package.json
```

## 개선 예정 (선택)

- [ ] 칵테일 상세 정보 모달/페이지
- [ ] 북마크 목록 정렬 및 삭제 UX 개선
- [ ] 반응형 레이아웃 점검
- [ ] 로딩/에러 상태 UI 보완

## 출처

- 칵테일 데이터: [TheCocktailDB](https://www.thecocktaildb.com/)
