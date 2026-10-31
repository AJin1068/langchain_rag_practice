# LangChain / RAG 실습

패스트캠퍼스 Agent 강의를 들으며 직접 따라 작성한 실습 코드입니다.
강의 원본 자료는 이 레포에 포함하지 않습니다.

## 폴더 구조

```
├── data/        실습용 자료 (PDF 등)
├── notebooks/
│   ├── part1_rag/              Part 1. RAG 기초
│   ├── part2_agent_framework/  Part 2. 에이전트 프레임워크
│   └── part3_multi_agent/      Part 3. 멀티 에이전트
└── notes/       강의 메모
```

## 처음 한 번 준비하기

1. 가상환경 만들기: `python -m venv venv`
2. 가상환경 켜기
   - Mac: `source venv/bin/activate`
   - Windows: `venv\Scripts\activate`
3. 설치: `pip install -r requirements.txt`
4. `.env.example`을 복사해서 `.env`로 이름을 바꾸고 OpenAI 키 적기
5. 실행: `jupyter notebook`

## 진도

- [ ] Part 1. LangChain으로 Basic RAG
- [ ] Part 1. LangGraph로 Basic RAG
