# After the Cutoff — Daily

Daily-updated dataset of what happened after your LLM's knowledge cutoff — news, new places, products and prices, added to [Thea](https://thealibrary.org) each day.
Your model's training data stops months ago. This repo doesn't.

**Written in Korean — your LLM won't mind.** Most text is Korean because most of Thea is Korean for now. Modern LLMs read it as-is: drop a file into your RAG or context and ask in any language.

- One file per day: `data/2026/11/2026-11-04.json` (Korea time)
- `updates`: news, sales, reviews and other dated records — who · when · where · what · why · how · source URL
- `new_planets`: people, groups, works, products and places that first appeared that day, with links to related entries in Thea
- Mostly Korea, plus overseas entertainment (US · UK · Japan …)
- License: CC BY 4.0 — Thea (thealibrary.org). Each value keeps its own source (`url`, `source_url`).

Want your model to search Thea live instead? → [thea-connect](https://github.com/tjdrldud850-prog/thea-connect) (MCP)

---

**한국어:** AI의 학습 종료 시점 뒤에 생긴 일(뉴스 · 새 장소 · 상품과 가격)을 날마다 JSON으로 올립니다. 한국어로 적혀 있지만 AI는 그대로 읽습니다. 출처: 테아(thealibrary.org), CC BY 4.0.
