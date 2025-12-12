---
permalink: /
title: ""
excerpt: "About me"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
.page__content {
  font-size: 0.95rem;
  line-height: 1.65;
}
.section-heading {
  font-size: 1.32rem;
  letter-spacing: 0.01em;
  font-weight: 700;
  margin: 1.4em 0 0.6em;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  border-bottom: none;
  padding-bottom: 0;
}
.section-heading::after {
  content: "";
  flex: 1;
  height: 1px;
  background: linear-gradient(90deg, rgba(89,139,231,0.35), rgba(89,139,231,0));
}
.card {
  background: #f8f9fc;
  border: 1px solid #e5e8f3;
  border-radius: 12px;
  box-shadow: 0 8px 18px rgba(0, 0, 0, 0.06);
  padding: 14px 16px;
}
.highlight-card {
  background: linear-gradient(135deg, #f3f6ff 0%, #eaf0ff 100%);
  border: 1px solid #d7e2ff;
  padding: 14px 16px;
  border-radius: 12px;
  box-shadow: 0 8px 18px rgba(0, 0, 0, 0.08);
  margin: 14px 0 18px;
  text-align: center;
  font-weight: 500;
}
.news-box {
  max-height: 260px;
  overflow-y: auto;
  padding: 2px 0;
  margin-bottom: 18px;
}
.news-box ul {
  list-style: disc;
  padding-left: 1.5rem;
  margin: 0.75rem 0;
}
.news-hint {
  text-align: right;
  font-size: 0.82rem;
  color: #9aa3b5;
  margin: -6px 0 6px;
}
.pub-title {
  font-size: 1.08rem;
  font-weight: 700;
}
.pub-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.pub-item {
  padding: 0 0 1rem;
  margin-bottom: 1rem;
  border-bottom: 1px solid #e8ebf3;
}
.pub-item:last-child {
  border-bottom: none;
  margin-bottom: 0.2rem;
  padding-bottom: 0.2rem;
}
.experience-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.experience-list li {
  margin-bottom: 0.55rem;
}
.entry-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.entry {
  padding: 0.75rem 0;
}
.entry:last-child {
  border-bottom: none;
}
.entry .entry__meta {
  font-size: 0.88rem;
  color: #6c7380;
  margin-bottom: 0.25rem;
}
.entry .entry__title {
  font-weight: 700;
}
.entry .entry__details {
  margin: 0.2rem 0 0.1rem;
}
.about-photo {
  float: right;
  width: clamp(220px, 32vw, 300px);
  max-width: 300px;
  height: auto;
  margin: 6px 0 12px 22px;
  border-radius: 10px;
  box-shadow: 0 10px 24px rgba(0, 0, 0, 0.12);
}
@media (max-width: 700px) {
  .about-photo {
    float: none;
    display: block;
    margin: 8px auto 16px;
  }
}
.quick-links {
  margin: 0.4em 0 1em;
  font-size: 0.92rem;
  color: #4b4b4b;
  padding: 0;
}
.quick-links .divider {
  color: #b0b7c3;
  margin: 0 0.35em;
}
.quick-links {
  margin: 0.4em 0 1em;
  font-size: 0.92rem;
  color: #4b4b4b;
  text-align: center;
}
.quick-links .divider {
  color: #b0b7c3;
  margin: 0 0.35em;
}
.page__content a {
  color: #598BE7;
  text-decoration: none;
}
.page__content a:hover,
.page__content a:focus {
  text-decoration: underline;
}
</style>

<h1 class="hero-title">Rikiya Takehi</h1>
<div class="hero-subtitle">4th year Undergraduate Student at Waseda University</div>
<img src="{{ '/images/iclrphoto.jpg' | prepend: site.baseurl }}" alt="Rikiya Takehi" class="about-photo">
<p>My research has revolved around <strong>IR</strong>, <strong>NLP</strong>, and <strong>ML</strong>. I am interested in building reliable AI systems, including LLMs, LLM Agents, RecSys, and retrievers.</p>
<p>I am an undergraduate student at Waseda University, supervised by <a href="http://sakailab.com/tetsuya/">Prof. Tetsuya Sakai</a>. I am now also at <a href="https://www.mixedbread.com/">Mixedbread</a>. Previously, I was a guest researcher at <a href="https://www.nist.gov/">NIST</a> working with <a href="https://www.nist.gov/people/ian-soboroff">Dr. Ian Soboroff</a> and <a href="https://www.nist.gov/people/ellen-m-voorhees">Dr. Ellen Voorhees</a>, and I have collaborated with <a href="https://841.io/">Prof. Fernando Diaz</a> of CMU LTI on retrieval rankings. I co-organize the <a href="https://trec-product-search.github.io/index.html">Product Search and Recommendations Track</a> at TREC.</p>

My first two years of graduate studies will be fully funded by the [Toyota PhD Fellowship](https://www.toyotariken.jp/overseas/).

<div class="quick-links">
  <a href="{{ site.author.cv }}">CV</a><span class="divider">|</span>
  <a href="mailto:rikiya.takehi@fuji.waseda.jp">Email</a><span class="divider">|</span>
  <a href="https://twitter.com/{{ site.author.twitter }}">Twitter</a><span class="divider">|</span>
  <a href="{{ site.author.googlescholar }}">Google Scholar</a><span class="divider">|</span>
  <a href="https://github.com/{{ site.author.github }}">Github</a>
</div>


<h2 class="section-heading" id="news">News</h2>

<div class="news-hint">scroll ↓</div>
<div class="news-box">
  <ul>
    <li><strong>Oct.2025</strong>: First authored full paper <a href="https://arxiv.org/abs/2510.22681">Diversity as Risk Minimization</a> got accepted to <strong>WSDM 2026</strong>.</li>
    <li><strong>Oct.2025</strong>: Released two open-source ColBERT models <a href="https://huggingface.co/mixedbread-ai/mxbai-edge-colbert-v0-17m">mxbai-edge-colbert-v0-17m</a> and <a href="https://huggingface.co/mixedbread-ai/mxbai-edge-colbert-v0-32m">mxbai-edge-colbert-v0-32m</a>. Tech report <a href="https://arxiv.org/abs/2510.14880">here</a>.</li>
    <li><strong>Aug.2025</strong>: My co-authored paper got accepted to CIKM 2025</li>
    <li><strong>Aug.2025</strong>: Started research internship at <a href="https://www.mixedbread.com/">Mixedbread</a>.</li>
    <li><strong>Jul.2025</strong>: Selected as a <strong>Toyota PhD Fellow: 2 yrs of full funding</strong>.</li>
    <li><strong>Jul.2025</strong>: Gave an invited talk (w/ Prof. ChengXiang Zhai) at SIGIR 2025 eCOM Workshop invited by Dr. Tracy Holloway King.</li>
    <li><strong>Jun.2025</strong>: Invited as a panelist at NTCIR 2025 with Prof. Maarten De Rijke, Prof. Mark Sanderson, Prof. Charles Clarke, & Prof. Ian Soboroff.</li>
    <li><strong>Jun.2025</strong>: Gave an invited talk at EVIA 2025 about <strong>Using LLMs as Assistants for Building Test Collections</strong> invited by Prof. Charles Clarke, Prof. Noriko Kando, & Prof. Makoto Kato. Slides can be found <a href="https://drive.google.com/file/d/1aoF8ZOxFj3EcjXyw07yiDztj5HP_xbYf/view?usp=sharing">here</a>.</li>
    <li><strong>Apr.2025</strong>: First authored full paper <strong>LLM-Assisted Relevance Assessments: When Should We Ask LLMs for Help?</strong> got accepted to <strong>SIGIR 2025</strong>!!</li>
    <li><strong>Jan.2025</strong>: First authored full paper <strong>General Framework for Off-Policy Learning with Partially-Observed Reward</strong> got accepted to <strong>ICLR 2025</strong>.</li>
    <li><strong>Nov.2024</strong>: Gave an invited talk at NII about <strong>Using LLMs as Assistants for Building Test Collections</strong> invited by Prof. Noriko Kando.</li>
    <li><strong>Nov.2024</strong>: First authored paper <a href="https://arxiv.org/abs/2411.06877">LLM-Assisted Relevance Assessments: When Should We Ask LLMs for Help?</a> preprint available on arXiv.</li>
    <li><strong>Oct.2024</strong>: Started research internship at <a href="https://www.cyberagent.co.jp/en/service/ai/">CyberAgent AI Lab.</a> Algorithm Team.</li>
    <li><strong>Aug.2024</strong>: Gave an invited talk at UMD College Park about <strong>Nugget-Based Evaluation and the Use of LLMs</strong> invited by Prof. Douglas Oard.</li>
    <li><strong>Oct.2023</strong>: First-authored paper <a href="https://doi.org/10.48550/arXiv.2310.00410">Open-Domain Dialogue Quality Evaluation: Deriving Nugget-level Scores from Turn-level Scores</a> accepted to <a href="http://www.sigir-ap.org/sigir-ap-2023/">SIGIR AP 2023</a>.</li>
  </ul>
</div>

<h2 class="section-heading" id="publications">Publications</h2>

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=9rS9VIYAAAAJ&hl=en).

<ol class="pub-list">
  <li class="pub-item">
    <span class="pub-title">Diversification as Risk Minimization</span><br>
    <strong>Rikiya Takehi</strong>, Fernando Diaz, Tetsuya Sakai. 2025.<br>
    <em>WSDM 2026</em>.<br>
    <a href="https://arxiv.org/abs/2510.22681">arXiv</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">General Framework for Off-Policy Learning with Partially-Observed Reward</span><br>
    <strong>Rikiya Takehi</strong>, Kosuke Kawakami, Masahiro Asami, Yuta Saito. 2025.<br>
    <em>ICLR 2025</em>.<br>
    <a href="https://arxiv.org/abs/2506.14439">arXiv</a> | <a href="https://openreview.net/forum?id=mUbYof5MKp">OpenReview</a> | <a href="https://iclr.cc/virtual/2025/poster/28461">presentation</a> | <a href="https://drive.google.com/file/d/106SG0z4k2d4iA2BwbdVRL4EOi--jDSSX/view?usp=sharing">poster</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">LLM‑Assisted Relevance Assessments: When Should We Ask LLMs for Help?</span><br>
    <strong>Rikiya Takehi</strong>, Ellen M. Voorhees, Tetsuya Sakai, and Ian Soboroff. 2025.<br>
    <em>SIGIR 2025</em>.<br>
    <a href="https://arxiv.org/abs/2411.06877">arXiv</a> | <a href="https://drive.google.com/file/d/1aoF8ZOxFj3EcjXyw07yiDztj5HP_xbYf/view">slides</a> | <a href="https://github.com/RikiyaT/LARA">code</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">Open-Source LLM-based Relevance Assessment vs. Highly Reliable Manual Relevance Assessment: A Case Study</span><br>
    Tetsuya Sakai, Khant Myoe Rain, <strong>Rikiya Takehi</strong>, Sijie Tao, Youngin Song. 2025.<br>
    <em>CIKM 2025</em>.<br>
    <a href="https://dl.acm.org/doi/pdf/10.1145/3746252.3760934">proceedings</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">Open-Domain Dialogue Quality Evaluation: Deriving Nugget-level Scores from Turn-level Scores</span><br>
    <strong>Rikiya Takehi</strong>, Akihisa Watanabe, and Tetsuya Sakai. 2023.<br>
    <em>SIGIR-AP 2023</em>.<br>
    <a href="https://github.com/RikiyaT/Nugget-Level-Evaluation">code</a> | <a href="https://drive.google.com/file/d/1M194h7nCFwUBVA3eqzapTNneDPFH4zUs/view?usp=sharing">poster</a> | <a href="https://RikiyaT.github.io/files/nugeval/slides.pdf">slides</a> | <a href="https://dl.acm.org/doi/abs/10.1145/3624918.3625338">proceedings</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">Fantastic (small) Retrievers and How to Train Them: mxbai-edge-colbert-v0 Tech Report.</span><br>
    <strong>Rikiya Takehi</strong>, Benjamin Clavié, Sean Lee, Aamir Shakir. 2025.<br>
    <em>Tech Report</em>.<br>
    <a href="https://arxiv.org/abs/2510.14880">Tech Report</a> | <a href="https://www.mixedbread.com/blog/edge-v0">Blog</a> | <a href="https://huggingface.co/mixedbread-ai/mxbai-edge-colbert-v0-17m">17M ColBERT model</a> | <a href="https://huggingface.co/mixedbread-ai/mxbai-edge-colbert-v0-32M">32M ColBERT model</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">Beyond Match Maximization and Fairness: Retention-Objectified Two-Sided Matching</span><br>
    <strong>Rikiya Takehi<sup>*</sup></strong>, Ren Kishimoto<sup>*</sup>, Koichi Tanaka, Masahiro Nomura, Riku Togashi, Yuta Saito. 2025.<br>
    <a href="https://drive.google.com/file/d/1Mwhyv-396KMUGveR-Wr1BuhzOGeN_fep/view?usp=sharing">preprint</a>
  </li>
  <li class="pub-item">
    <span class="pub-title">Objective-driven Calibrated Recommendations</span><br>
    <strong>Rikiya Takehi<sup>*</sup></strong>, Koichi Tanaka<sup>*</sup>, Ren Kishimoto, Masahiro Nomura, Riku Togashi, Yuta Saito. 2025.<br>
    <a href="https://drive.google.com/file/d/1-kSRjOcvsKpC07G3gScR-W36wq9FIuMi/view?usp=sharing">preprint</a>
  </li>
</ol>

<h2 class="section-heading" id="experience">Experience</h2>

<ul class="entry-list">
  <li class="entry">
    <div class="entry__meta">Aug 2025 – Present · CA, USA</div>
    <div class="entry__title">Research Intern, Mixedbread</div>
  </li>
  <li class="entry">
    <div class="entry__meta">Oct 2024 – Sep 2025 · Tokyo, Japan</div>
    <div class="entry__title">Research Intern, <a href="https://www.cyberagent.co.jp/en/service/ai/">CyberAgent AI Lab.</a> Algorithm Team</div>
  </li>
  <li class="entry">
    <div class="entry__meta">Oct 2023 – Sep 2024 · Maryland, US</div>
    <div class="entry__title">Guest Researcher, <a href="https://www.nist.gov/">NIST Retrieval Group</a></div>
  </li>
  <li class="entry">
    <div class="entry__meta">Sept 2023 – Oct 2024 · Tokyo, Japan</div>
    <div class="entry__title">Research Intern, <a href="https://www.hakuhodo-technologies.co.jp/">Hakuhodo Tech Inc.</a></div>
  </li>
</ul>

<h2 class="section-heading" id="talks">Invited Talks</h2>

<ul class="entry-list">
  <li class="entry">
    <div class="entry__meta">Jul 2025 · Invited by Dr. Tracy Holloway King (Adobe)</div>
    <div class="entry__title">SIGIR eCom Workshop 2025</div>
    <div class="entry__details"><em>Product Search and Recommendations</em> (with Prof. ChengXiang Zhai)</div>
  </li>
  <li class="entry">
    <div class="entry__meta">Jun 2025 · Invited by Prof. Charles Clarke (UWaterloo)</div>
    <div class="entry__title">EVIA 2025</div>
    <div class="entry__details"><em>Using LLMs as Assistants for Building Large Test Collections</em></div>
  </li>
  <li class="entry">
    <div class="entry__meta">Nov 2024 · Invited by Prof. Noriko Kando (NII)</div>
    <div class="entry__title">National Institute of Informatics</div>
    <div class="entry__details"><em>Using LLMs as Assistants for Building Test Collections (Trends and Problems of Test Collections)</em></div>
  </li>
  <li class="entry">
    <div class="entry__meta">Aug 2024 · Invited by Prof. Douglas Oard (UMD)</div>
    <div class="entry__title">University of Maryland, College Park</div>
    <div class="entry__details"><em>Nugget-Based Evaluation and the Use of LLMs</em></div>
  </li>
  <li class="entry">
    <div class="entry__meta">2025 · Panel</div>
    <div class="entry__title">NTCIR 2025 Panelist</div>
    <div class="entry__details">With Profs. Maarten de Rijke (UvA), Mark Sanderson (RMIT), Charles Clarke (UWaterloo), and Ian Soboroff (NIST).</div>
  </li>
</ul>

<!--
# Education
- **Waseda University** (2021-)
  - 3rd-year B.A student at Computer Science and Communications Engineering (English-based major)

# Languages
Japanese (native), English (fluent: TOEFL 110), French (fluent: CEFR/DELF B2)
-->
