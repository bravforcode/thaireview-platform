# ThaiReview Platform — AI + Blockchain Review Verification

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![WangchanBERTa](https://img.shields.io/badge/WangchanBERTa-FF6B35?style=for-the-badge&logo=huggingface&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Blockchain](https://img.shields.io/badge/Trust_Layer-Blockchain-7c3aed?style=for-the-badge)

> **Fake reviews die here.** Thai NLP (WangchanBERTa) + blockchain verification for authentic product reviews.

### Demo

![Demo](https://via.placeholder.com/1280x640/0f172a/38bdf8?text=ThaiReview+—+AI%2BBlockchain+Review+Verification+—+Add+docs/demo.gif)

### Architecture

```mermaid
graph TD
  A[Review Submission] --> B[Next.js Frontend]
  B --> C[WangchanBERTa Sentiment + Authenticity]
  C --> D{Authentic?}
  D -->|Yes| E[Anchor Hash on Blockchain]
  D -->|No| F[Flag + Review Queue]
  E --> G[(Immutable Review Ledger)]
```

### Results

| Metric | Value |
|---|---|
| **NLP** | WangchanBERTa (Thai SOTA) |
| **Trust** | Blockchain-anchored reviews |
| **Stack** | Next.js + Solidity |


---

**Phirawit Jitnarong — Strategic Full-Stack & AI Engineer**

xme176@gmail.com · 092-551-0427 · [LinkedIn](https://www.linkedin.com/in/%E0%B8%9E%E0%B8%B5%E0%B8%A3%E0%B8%A7%E0%B8%B4%E0%B8%8A%E0%B8%8D%E0%B9%8C-%E0%B8%88%E0%B8%B4%E0%B8%95%E0%B8%93%E0%B8%A3%E0%B8%87%E0%B8%84%E0%B9%8C-0000393a4) · [Fastwork](https://fastwork.co/user/bravforcode?source=search)

> Hiring for this stack? Let's talk — production hardened, 300k+ users shipped.