---
widget: blank
headless: true
weight: 20

title: Research
subtitle: Three connected directions in soft responsive materials

design:
  columns: "1"

advanced:
  css_id: research
---

<div class="research-theme-grid">
<article class="research-theme-card">
<div class="research-theme-figure"><img src="/media/research/hydrogels-transport.png" alt="Multiscale diagram of a water-rich hydrogel with an aerogel network and stable gas transport"></div>
<div class="research-theme-number">01</div>
<h3>Hydrogels &amp; Transport</h3>
<p>Water-rich polymer networks for controlled gas transport, water capture, and responsive swelling.</p>
<a href="/project/hydrogel-origami-for-awh/">Explore this theme →</a>
</article>
<article class="research-theme-card">
<div class="research-theme-figure"><img src="/media/research/soft-actuation.png" alt="Soft polymer structures deforming in response to light"></div>
<div class="research-theme-number">02</div>
<h3>Soft Actuation &amp; Robotics</h3>
<p>Molecular order and phase transitions translated into programmed motion and adaptive behavior.</p>
<a href="/project/spiropyran/">Explore this theme →</a>
</article>
<article class="research-theme-card">
<div class="research-theme-figure"><img src="/media/research/reconfigurable-architectures.png" alt="Reconfigurable cellular architecture with responsive molecular domains"></div>
<div class="research-theme-number">03</div>
<h3>Reconfigurable Architectures</h3>
<p>Responsive materials and geometry combined to create structures with programmable transformations.</p>
<a href="/project/cellular-metamaterials/">Explore this theme →</a>
</article>
</div>

<style>
.research-theme-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1.25rem; max-width: 1200px; margin: 1.5rem auto 1.2rem; }
.research-theme-card { display: flex; flex-direction: column; padding: 0 0 1.4rem; border: 1px solid #ddd; border-radius: 6px; overflow: hidden; background: #fff; transition: transform .2s ease, box-shadow .2s ease; }
.research-theme-card:hover { transform: translateY(-3px); box-shadow: 0 5px 18px rgba(0, 0, 0, .08); }
.research-theme-figure { display: flex; align-items: center; justify-content: center; height: 150px; padding: .45rem; background: #fff; overflow: hidden; }
.research-theme-figure img { display: block; width: 100%; height: 100%; object-fit: contain; }
.research-theme-card:nth-child(2) .research-theme-figure { background: #25354b; }
.research-theme-card:nth-child(3) .research-theme-figure { background: #111; }
.research-theme-number, .research-theme-card h3, .research-theme-card p, .research-theme-card a { margin-left: 1.4rem; margin-right: 1.4rem; }
.research-theme-number { margin-top: 1.2rem; margin-bottom: .35rem; color: #999; font-size: .78rem; font-weight: 700; letter-spacing: .08em; }
.research-theme-card h3 { margin-top: 0; margin-bottom: .6rem; font-size: 1.2rem; font-weight: 700; line-height: 1.25; }
.research-theme-card p { margin-bottom: 1rem; font-size: .94rem; line-height: 1.5; }
.research-theme-card a { margin-top: auto; font-weight: 650; text-decoration: none; }
.research-theme-card a:hover { text-decoration: underline; }
@media (max-width: 900px) {
.research-theme-grid { grid-template-columns: 1fr; }
.research-theme-figure { height: 190px; }
}
</style>
