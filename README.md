# 웹 프로그래밍: 미니 게임 포털

웹 프로그래밍 과목 기말 과제입니다. Flask로 로그인·회원가입·게임 목록 페이지를 만들고, HTML5 Canvas와 JavaScript로 작성한 미니 게임 6개를 연결했습니다.

| 경로 | 내용 |
|---|---|
| `웹 프로그래밍/main.ipynb` | Flask 앱 (노트북 셀로 작성). 라우트: `/`, `/sign-in`, `/sign-up`, `/login`, `/company`, `/contact`, `/products`, `/product_detail/<id>/`, `/save-log`, `/user-info`, `/logout` |
| `웹 프로그래밍/templates/` | Jinja 템플릿 8개 |
| `웹 프로그래밍/static/games/1.html` ~ `6.html` | Breakout과 Space Invader, 카드 맞추기, 리듬 게임, Canvas 게임, 테트리스, 미로 게임 |
| `웹 프로그래밍/static/` | CSS(Bootstrap), JS(jQuery, slick, Headroom), 이미지, 효과음 |

## 실행

검증하지 않은 절차입니다.

1. `pip install flask jupyter`
2. `웹 프로그래밍/` 폴더에서 `main.ipynb`를 열고 셀을 순서대로 실행합니다.

- 회원 정보는 DB 없이 전역 변수 하나(마지막 가입자 1명)에 저장되므로 서버를 다시 시작하면 사라집니다. 과제용 구조이며 실제 인증 용도가 아닙니다.
- `breakout` 브랜치에 `1.html` 수정 이력이 따로 있습니다.
- Bootstrap, jQuery 등 외부 라이브러리 파일과 일부 이미지·음원은 직접 만든 것이 아닙니다. 출처가 기록되어 있지 않습니다.
