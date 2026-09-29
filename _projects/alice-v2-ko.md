---
layout: page
title: ALICE v2
description: 기구 아키텍처 설계부터 조립과 시험까지 개발한 자율형 휴머노이드 축구 로봇.
img: assets/img/projects/alice-v2.jpg
importance: 1
category: humanoid
lang: ko
permalink: /projects/alice-v2/
---

<link rel="stylesheet" href="{{ '/assets/css/alice-project.css' | relative_url }}">

<article class="alice-showcase">
  <div class="alice-language" aria-label="언어 선택"><strong>한국어</strong><span aria-hidden="true">·</span><a href="{{ '/en/projects/alice-v2/' | relative_url }}" lang="en">English</a></div>

  <header class="alice-hero">
    <div>
      <p class="alice-eyebrow">Humanoid Robotics · Featured Project</p>
      <h1>자율형 휴머노이드 <span>ALICE v2</span></h1>
    </div>
    <div class="alice-hero-copy">
      <p class="alice-lede">자연스러운 이족 보행과 축구 임무를 위해 기구 아키텍처, 경량 구조, 센서 및 전자 시스템을 하나의 소형 플랫폼으로 통합한 로봇입니다.</p>
      <div class="alice-tags" aria-label="프로젝트 키워드"><span class="alice-tag">Mechanical Architecture</span><span class="alice-tag">20 DoF</span><span class="alice-tag">Creo</span><span class="alice-tag">ROS</span></div>
      <div class="alice-actions"><a class="alice-button primary" href="#development">개발 과정</a><a class="alice-button" href="#validation">검증 결과</a><a class="alice-button" href="{{ '/assets/pdf/jeonghoon-choi-portfolio.pdf' | relative_url }}" target="_blank" rel="noopener">전체 PDF</a></div>
    </div>
  </header>

  <figure class="alice-figure">
    <a href="{{ '/assets/img/projects/alice-v2.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/img/projects/alice-v2.jpg' | relative_url }}" alt="ALICE v2 휴머노이드의 전체 외형과 핵심 사양"></a>
    <figcaption>ALICE v2 플랫폼: 자율 보행과 축구 임무를 위한 20자유도 휴머노이드.</figcaption>
  </figure>

  <div class="alice-metrics" aria-label="하드웨어 사양">
    <div class="alice-metric"><strong>136 cm</strong><span>키</span></div><div class="alice-metric"><strong>20 kg</strong><span>무게</span></div><div class="alice-metric"><strong>20</strong><span>자유도</span></div><div class="alice-metric"><strong>6 DoF</strong><span>각 다리</span></div>
  </div>

  <section class="alice-section alice-intro-grid" id="overview">
    <div><p class="alice-eyebrow">Project Overview</p><h2>구조 설계와 시스템 통합을 함께 풀어낸 휴머노이드.</h2></div>
    <div class="alice-copy"><p>ALICE v2는 인공지능 기반의 자율주행 축구 로봇으로 개발됐습니다. 자연스러운 보행을 위한 6자유도 다리, 목표 중량과 필요 토크를 만족하는 경량 부품, 정비가 쉬운 모듈형 하지 구조를 설계했습니다.</p><p>카메라, 힘/토크 센서, 배터리, 메인 컴퓨터를 제한된 본체 공간에 배치하고, 설계부터 제작·조립·동작 시험까지 전체 하드웨어 개발 주기에 참여했습니다.</p></div>
    <div></div>
    <div class="alice-takeaways" aria-label="핵심 기여">
      <article class="alice-card"><span class="alice-card-index">01 · Architecture</span><h3>6자유도 하지 아키텍처</h3><p>보행 움직임과 관절 가동 범위를 고려해 다리 관절 축과 구조를 정의했습니다.</p></article>
      <article class="alice-card"><span class="alice-card-index">02 · Integration</span><h3>센서·전자 시스템 패키징</h3><p>전신 카메라, 하지 센서, 배터리와 컴퓨터를 정비 가능한 구조로 통합했습니다.</p></article>
      <article class="alice-card"><span class="alice-card-index">03 · Validation</span><h3>조립에서 보행 시험까지</h3><p>제작 공차와 조립성을 확인하고, 완성된 플랫폼의 전신 동작과 축구 임무를 검증했습니다.</p></article>
    </div>
  </section>

  <section class="alice-section alice-band" id="development">
    <div class="alice-section-heading"><p class="alice-eyebrow">Engineering Decisions</p><h2>경량화, 정렬, 정비성을 하나의 구조에 담았습니다.</h2></div>
    <div class="alice-method-grid">
      <article class="alice-card"><span class="alice-card-index">01</span><h3>관절 정렬</h3><p>X·Y·Z 회전축이 각 평면에서 일직선으로 교차하도록 설계해 기구학적 구조를 명확히 했습니다.</p></article>
      <article class="alice-card"><span class="alice-card-index">02</span><h3>경량 설계</h3><p>AL6061을 중심으로 부품을 저하중 설계해 모터 용량과 비용을 관리했습니다.</p></article>
      <article class="alice-card"><span class="alice-card-index">03</span><h3>모듈과 공차</h3><p>거치대와의 호환, 부품 간 삽입 구조를 적용해 반복 시험과 누적 공차 관리를 쉽게 했습니다.</p></article>
      <article class="alice-card"><span class="alice-card-index">04</span><h3>스마트 패키징</h3><p>무릎·발목 공간을 위해 베벨기어를 선정하고 가슴 내부에 전장 공간을 확보했습니다.</p></article>
    </div>
    <figure class="alice-figure"><a href="{{ '/assets/img/projects/alice-v2-development.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/img/projects/alice-v2-development.jpg' | relative_url }}" alt="ALICE v2 3D 모델링, 구조 및 RoboCup 조립 과정"></a><figcaption>3D 모델링, 주요 부품 배치, RoboCup 현장 조립으로 이어진 설계 과정.</figcaption></figure>
  </section>

  <section class="alice-section" id="validation">
    <div class="alice-section-heading"><p class="alice-eyebrow">Build & Validation</p><h2>설계를 제작 가능한 하드웨어로 완성하고 실제 동작으로 확인했습니다.</h2></div>
    <div class="alice-validation-grid">
      <figure class="alice-figure"><a href="{{ '/assets/img/projects/alice-v2-validation.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/img/projects/alice-v2-validation.jpg' | relative_url }}" alt="ALICE v2 부품 선정, 조립, 가공 및 동작 시험 프로세스"></a><figcaption>부품 선정 → 설계 조건 정의 → 가공 발주 → 조립 및 동작 시험의 4단계 개발 프로세스.</figcaption></figure>
      <div class="alice-result"><p class="alice-eyebrow">Outcome</p><h3>설계부터 로봇 동작까지 연결</h3><ul><li>안전계수 2.5를 기준으로 모터와 기계 부품 선정</li><li>하지 조립 전 배치와 전체 조립성 검토</li><li>외장 장착 후 전신 자립 상태 확인</li><li>실제 축구 환경에서 전신 동작 시험</li></ul></div>
    </div>
  </section>

  <footer class="alice-cta"><p>ALICE v2 외의 휴머노이드, 재활 및 인터랙션 로봇도 확인해 보세요.</p><div class="alice-actions"><a class="alice-button" href="{{ '/projects/' | relative_url }}">전체 프로젝트</a><a class="alice-button primary" href="{{ '/cv/' | relative_url }}">포트폴리오 PDF</a></div></footer>
</article>
