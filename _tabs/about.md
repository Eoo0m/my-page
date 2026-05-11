---
title: About
icon: fas fa-info-circle
order: 4
---

## 엄준서

**ML Engineer** — 추천 시스템, 표현학습, AI 시스템 설계

추천 시스템·표현학습·AI 기반 시스템 설계에 관심이 많은 ML 엔지니어입니다. 다양한 논문의 방법론을 직접 구현해 성능 개선으로 연결하고, 80K 트랙 규모의 음악 추천 시스템을 설계·배포·운영한 경험이 있습니다. 모델을 프로덕션 환경에서 실제 사용자 가치로 전환하는 데 집중합니다.

---

### Experience

**SK ON** | Intern, AI & Digital Transformation | 2026.02 - 2026.04
- 윤활유 수요 예측 모델 개발 — LightGBM 기반, 고객 엔트로피 활용 WAPE 20% → 15% 개선
- Databricks 기반 멀티모달 RAG 시스템 설계 — 성공률 83%

**Generative Lab** | Software Engineer | 2025.06 - 2025.08
- CJ Logistics API 기반 tool-calling agent로 CS 상담 자동화
- 월 10만 건 AI 상담 로그 분석 파이프라인 구축

---

### Education

**Yonsei University** | 2020.03 - 2026.08
- Bachelor of Industrial Engineering
- YBIGTA DS, Lead of Education

---

### Skills

| 분야 | 기술 |
|------|------|
| Languages | Python, SQL |
| ML/DL | PyTorch, HuggingFace, LangChain |
| Infra | AWS, NCP, Linux, GitHub Actions, Supabase(pgvector), Cloudflare Pages |
| Backend/API | FastAPI, Uvicorn |

---

### Portfolio

- [Dynplayer Portfolio (PDF)]({{ site.baseurl }}/assets/Dynplayer.pdf){:target="_blank"}
- [Portfolio (PDF)]({{ site.baseurl }}/assets/portfolio.pdf){:target="_blank"}

### CV

<div style="margin-bottom: 12px;">
  <button onclick="switchCV('ko')" style="padding:6px 16px; border:1px solid #ddd; border-radius:6px; background:#333; color:#fff; cursor:pointer; margin-right:4px;">한국어</button>
  <button onclick="switchCV('en')" style="padding:6px 16px; border:1px solid #ddd; border-radius:6px; background:transparent; color:inherit; cursor:pointer;">English</button>
</div>

<iframe id="cv-frame" src="/my-page/assets/CV.pdf" style="width:100%; height:800px; border:1px solid #ddd; border-radius:8px;"></iframe>

<script>
function switchCV(lang) {
  document.getElementById('cv-frame').src = lang === 'en' ? '/my-page/assets/CV_eng.pdf' : '/my-page/assets/CV.pdf';
  var btns = document.querySelectorAll('button[onclick^="switchCV"]');
  btns.forEach(function(b){ b.style.background='transparent'; b.style.color='inherit'; });
  event.target.style.background='#333'; event.target.style.color='#fff';
}
</script>

---

**Contact:** [jseom818@gmail.com](mailto:jseom818@gmail.com) · [GitHub](https://github.com/Eoo0m) · [Dynplayer](https://dynplayer.win)
