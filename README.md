# 핸디컴퍼니 콘텐츠 제작 라이브러리

마케팅팀 전원이 동일한 퀄리티로 장면별 기획안과 촬영 가이드라인을 만들기 위한 Claude Code 라이브러리입니다.

---

## 시작하기

### 1. 이 폴더를 Claude Code로 열기
```
Claude Code 앱 → Open Project → 이 폴더 선택
```

### 2. 커맨드 실행

| 상황 | 커맨드 |
|------|--------|
| 처음부터 전부 (기획안 + 가이드라인) | `/content-plan` |
| 기획안만 | `/scene-plan` |
| 가이드라인만 (기획안 이미 있을 때) | `/shooting-guide` |

---

## 폴더 구조

```
handy-content-studio/
├── CLAUDE.md                      ← 전역 규칙 (자동 로드, 수정 시 팀장 확인)
├── .claude/commands/
│   ├── content-plan.md            ← /content-plan 커맨드
│   ├── scene-plan.md              ← /scene-plan 커맨드
│   └── shooting-guide.md         ← /shooting-guide 커맨드
├── examples/
│   ├── scene-plan/                ← 잘 된 기획안 예시 (퀄리티 기준)
│   └── shooting-guide/            ← 잘 된 가이드라인 예시
├── guardrails/
│   ├── _template.md               ← 신규 고객사 온보딩 양식
│   ├── helsjangbu.md
│   └── ...                        ← 고객사별 금지표현·수치 관리
└── README.md
```

---

## 신규 고객사 온보딩

1. `guardrails/_template.md` 복사
2. 파일명을 고객사명으로 변경 (예: `naabom.md`)
3. 내용 채우기
4. PR 올리거나 팀장에게 확인 받기

---

## 규칙 수정이 필요할 때

`CLAUDE.md`는 전원에게 적용되는 파일입니다.
수정 전 반드시 팀장(신민정) 확인 후 진행하세요.
