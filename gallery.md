---
layout: page
title: "📷 Gallery"
permalink: /gallery/
---

<style>
  .gallery-container {
    display: flex;
    flex-wrap: wrap;
    gap: 30px; /* 卡片之间的间距 */
    justify-content: center; /* 居中对齐 */
  }
  
  .gallery-card {
    width: 300px; /* 每个卡片的宽度 */
    background: #fff;
    border: 1px solid #eee;
    border-radius: 8px; /* 圆角 */
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05); /* 淡淡的阴影 */
    transition: transform 0.2s; /* 动画效果 */
  }
  
  .gallery-card:hover {
    transform: translateY(-5px); /* 鼠标悬停时上浮 */
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }

  .gallery-img {
    width: 100%;
    height: 200px; /* 图片高度统一，防止参差不齐 */
    object-fit: cover; /* 保证图片填满且不变形 */
    display: block;
  }

  .gallery-info {
    padding: 15px;
  }

  .gallery-title {
    margin: 0 0 8px 0;
    font-size: 16px;
    font-weight: bold;
    color: #333;
  }

  .gallery-desc {
    font-size: 14px;
    color: #666;
    line-height: 1.5;
    margin: 0;
  }
</style>

<p style="text-align: center; color: #666; margin-bottom: 40px;">
  记录生活的精彩瞬间与科研成果。<br>
  <small>Capturing moments in science and life.</small>
</p>

<div class="gallery-container">

  <div class="gallery-card">
    <img src="/assets/images/pic_haoyu_cat.jpg" class="gallery-img" alt="Conference">
    <div class="gallery-info">
      <h3 class="gallery-title">猫咖</h3>
      <p class="gallery-desc">
        2026年1月，我们每次出行基本都会去猫咖，cat是世界的小精灵。
      </p>
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/banner1.jpg" class="gallery-img" alt="Conference">
    <div class="gallery-info">
      <h3 class="gallery-title">青岛海底世界</h3>
      <p class="gallery-desc">
        2026年1月，新年伊始，我和浩宇参观了青岛海底世界。我很喜欢大海。
      </p>
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/banner2.jpg" class="gallery-img" alt="Team Building">
    <div class="gallery-info">
      <h3 class="gallery-title">玄武湖游玩</h3>
      <p class="gallery-desc">
        2025年4月，处在樱花季的南京很美（樱花季在清明节前后，可别错过）。
      </p>
    </div>
  </div>

  <div class="gallery-card">
    <img src="/assets/images/banner4.jpg" class="gallery-img" alt="Research">
    <div class="gallery-info">
      <h3 class="gallery-title">莫干山民宿</h3>
      <p class="gallery-desc">
        2024年4月，在莫干山游玩，民宿中的小温暖。
      </p>
    </div>
  </div>

</div>