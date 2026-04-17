---
layout: default
title: "BeautsGO - Korean Beauty Booking Guide"
description: "Book appointments at 900+ top-rated Korean dermatology & plastic surgery clinics in Seoul"
---

<style>
.hero {
  text-align: center;
  padding: 60px 20px 40px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border-radius: 12px;
  margin-bottom: 40px;
}
.hero h1 { font-size: 2.2em; margin-bottom: 12px; }
.hero p { font-size: 1.1em; opacity: 0.9; max-width: 600px; margin: 0 auto 24px; }
.hero .cta {
  display: inline-block;
  background: white;
  color: #764ba2;
  padding: 12px 32px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  font-size: 1em;
  transition: transform 0.2s;
}
.hero .cta:hover { transform: scale(1.05); }
.stats {
  display: flex;
  justify-content: center;
  gap: 40px;
  margin-top: 24px;
  flex-wrap: wrap;
}
.stats .stat-item {
  text-align: center;
}
.stats .stat-num {
  font-size: 2em;
  font-weight: bold;
  display: block;
}
.stats .stat-label {
  font-size: 0.85em;
  opacity: 0.8;
}
.languages {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-top: 32px;
  flex-wrap: wrap;
}
.languages a {
  display: inline-block;
  padding: 8px 20px;
  border: 2px solid rgba(255,255,255,0.6);
  border-radius: 24px;
  color: white;
  text-decoration: none;
  font-size: 0.9em;
  transition: all 0.2s;
}
.languages a:hover {
  background: rgba(255,255,255,0.2);
  border-color: white;
}
.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-bottom: 40px;
}
.feature-card {
  border: 1px solid #e1e4e8;
  border-radius: 10px;
  padding: 24px;
  text-align: center;
  transition: box-shadow 0.2s;
}
.feature-card:hover { box-shadow: 0 4px 12px rgba(0,0,0,0.1); }
.feature-card .icon { font-size: 2em; margin-bottom: 8px; }
.feature-card h3 { font-size: 1em; margin: 0 0 6px; }
.feature-card p { font-size: 0.85em; color: #586069; margin: 0; }
.howto {
  background: #f6f8fa;
  border-radius: 10px;
  padding: 30px;
  margin-bottom: 40px;
}
.howto h2 { margin-top: 0; }
.howto ol { padding-left: 20px; }
.howto li { margin-bottom: 10px; line-height: 1.6; }
</style>

<div class="hero">
  <h1>🏥 BeautsGO Korean Beauty Booking</h1>
  <p>Book appointments at 900+ top-rated Korean dermatology & plastic surgery clinics in Seoul — directly from your AI assistant.</p>
  <a href="https://github.com/BeautsGO/beautsgo-booking" class="cta">⭐ View on GitHub</a>
  <div class="stats">
    <div class="stat-item">
      <span class="stat-num">900+</span>
      <span class="stat-label">Clinics</span>
    </div>
    <div class="stat-item">
      <span class="stat-num">4</span>
      <span class="stat-label">Languages</span>
    </div>
    <div class="stat-item">
      <span class="stat-num">5</span>
      <span class="stat-label">Booking Channels</span>
    </div>
  </div>
  <div class="languages">
    <a href="clinics/zh/">🇨🇳 中文</a>
    <a href="clinics/en/">🇺🇸 English</a>
    <a href="clinics/ja/">🇯🇵 日本語</a>
    <a href="clinics/th/">🇹🇭 ไทย</a>
  </div>
</div>

<div class="features">
  <div class="feature-card">
    <div class="icon">🔍</div>
    <h3>Smart Search</h3>
    <p>Search by clinic name, English name, Pinyin, or procedure type</p>
  </div>
  <div class="feature-card">
    <div class="icon">📅</div>
    <h3>Direct Booking</h3>
    <p>Submit appointments via API — no browser or app download needed</p>
  </div>
  <div class="feature-card">
    <div class="icon">💰</div>
    <h3>Price Check</h3>
    <p>View up-to-date price lists for every clinic</p>
  </div>
  <div class="feature-card">
    <div class="icon">💬</div>
    <h3>Live Consultation</h3>
    <p>Connect with clinic customer service instantly</p>
  </div>
</div>

<div class="howto">
  <h2>🚀 How to Use</h2>
  <ol>
    <li>Install this skill in your AI assistant (Claude Code, WorkBuddy, or any OpenClaw-compatible client)</li>
    <li>Tell the AI which clinic or procedure you're interested in, e.g. "帮我预约JD皮肤科" or "I want Botox in Seoul"</li>
    <li>The AI will match the best clinic, guide you through booking, and submit your appointment directly</li>
  </ol>
  <p><strong>Popular procedures:</strong> Laser treatment, Botox, Skin boosters (水光针), Double eyelid surgery, Rhinoplasty, Anti-aging, Acne treatment, and more.</p>
</div>
