---
layout: archive
title: "Paper Highlight"
permalink: /paper-highlights/pavement-defect/
author_profile: true
---

<style>
  .paper-slide-wrap {
    max-width: 1120px;
    margin: 0 auto 2rem;
  }

  .paper-slide {
    aspect-ratio: 16 / 9;
    min-height: 620px;
    padding: 34px 42px;
    border: 1px solid #d7dde5;
    border-radius: 8px;
    background:
      linear-gradient(135deg, rgba(12, 77, 110, 0.08), rgba(230, 238, 231, 0.75)),
      #ffffff;
    box-shadow: 0 18px 42px rgba(36, 48, 60, 0.12);
    display: grid;
    grid-template-rows: auto 1fr auto;
    gap: 24px;
  }

  .paper-slide__kicker {
    margin: 0 0 8px;
    color: #2d6a72;
    font-size: 0.82rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .paper-slide h1 {
    margin: 0;
    max-width: 980px;
    color: #1d2730;
    font-size: clamp(1.7rem, 2.8vw, 2.55rem);
    line-height: 1.14;
  }

  .paper-slide__meta {
    margin-top: 12px;
    color: #53616f;
    font-size: 0.98rem;
  }

  .paper-slide__body {
    display: grid;
    grid-template-columns: 1.03fr 1.3fr;
    gap: 24px;
    min-height: 0;
  }

  .paper-slide__problem {
    padding: 24px;
    border-left: 5px solid #2d6a72;
    background: rgba(255, 255, 255, 0.72);
  }

  .paper-slide__problem h2,
  .paper-slide__innovations h2 {
    margin: 0 0 14px;
    color: #1f3438;
    font-size: 1.08rem;
  }

  .paper-slide__problem p {
    margin: 0 0 18px;
    color: #26343e;
    font-size: 1.05rem;
    line-height: 1.58;
  }

  .paper-slide__metric {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 10px;
  }

  .paper-slide__metric strong {
    display: block;
    color: #b8422e;
    font-size: 1.45rem;
    line-height: 1.1;
  }

  .paper-slide__metric span {
    color: #52606d;
    font-size: 0.78rem;
  }

  .paper-slide__innovations {
    display: grid;
    gap: 12px;
  }

  .paper-slide__point {
    padding: 16px 18px;
    border: 1px solid rgba(45, 106, 114, 0.2);
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.82);
  }

  .paper-slide__point h3 {
    margin: 0 0 6px;
    color: #1f3438;
    font-size: 0.98rem;
  }

  .paper-slide__point p {
    margin: 0;
    color: #42515e;
    font-size: 0.91rem;
    line-height: 1.46;
  }

  .paper-slide__footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 16px;
    color: #53616f;
    font-size: 0.86rem;
  }

  .paper-slide__footer a {
    color: #2d6a72;
    font-weight: 700;
  }

  @media (max-width: 900px) {
    .paper-slide {
      aspect-ratio: auto;
      min-height: 0;
      padding: 24px;
    }

    .paper-slide__body {
      grid-template-columns: 1fr;
    }

    .paper-slide__footer {
      align-items: flex-start;
      flex-direction: column;
    }
  }
</style>

<div class="paper-slide-wrap">
  <section class="paper-slide" aria-label="Paper highlight slide">
    <header>
      <p class="paper-slide__kicker">Paper Highlight | Urban Pavement Defect Assessment</p>
      <h1>From street-view sensing to maintenance decisions: A knowledge-based engineering informatics framework for urban pavement defect assessment</h1>
      <p class="paper-slide__meta">Linchao Li, Bangxing Li, Jiazhen Liu, Bowen Du | Developments in the Built Environment, 2026, 26, 100920</p>
    </header>

    <div class="paper-slide__body">
      <section class="paper-slide__problem">
        <h2>Core Contribution</h2>
        <p>
          The study turns ordinary street-view imagery into an engineering decision pipeline for pavement maintenance, moving beyond visual defect detection toward scalable, evidence-based urban road assessment.
        </p>
        <div class="paper-slide__metric">
          <div>
            <strong>3,798</strong>
            <span>annotated images</span>
          </div>
          <div>
            <strong>6,000+</strong>
            <span>crack and pothole targets</span>
          </div>
          <div>
            <strong>YOLOv8+</strong>
            <span>enhanced detector</span>
          </div>
          <div>
            <strong>+4.7%</strong>
            <span>mAP improvement</span>
          </div>
        </div>
      </section>

      <section class="paper-slide__innovations">
        <h2>Innovation Points</h2>
        <div class="paper-slide__point">
          <h3>1. Street-view-based pavement sensing</h3>
          <p>Uses widely available street-view images to reduce dependence on manual inspection or specialized survey vehicles.</p>
        </div>
        <div class="paper-slide__point">
          <h3>2. Dataset tailored to urban defect complexity</h3>
          <p>Builds a custom annotated dataset covering cracks and potholes under low resolution, cluttered backgrounds, and diverse street scenes.</p>
        </div>
        <div class="paper-slide__point">
          <h3>3. Enhanced YOLOv8 for small and subtle targets</h3>
          <p>Improves feature preservation, multi-scale fusion, and detection-head awareness to better capture fine-grained pavement defects.</p>
        </div>
        <div class="paper-slide__point">
          <h3>4. Detection results linked to maintenance decisions</h3>
          <p>Frames AI detection as part of a knowledge-based engineering informatics workflow for practical pavement assessment and prioritization.</p>
        </div>
      </section>
    </div>

    <footer class="paper-slide__footer">
      <span>Summary prepared for research communication and homepage presentation.</span>
      <a href="https://doi.org/10.1016/j.dibe.2026.100920">Paper DOI</a>
    </footer>
  </section>
</div>
