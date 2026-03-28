---
layout: default
title: Home
---

<style>
  /* 模拟侧边栏布局逻辑 */
  @media screen and (min-width: 64em) {
    .main-content { display: flex; gap: 40px; }
    .sidebar { width: 280px; position: sticky; top: 20px; align-self: flex-start; }
    .content-area { flex: 1; }
  }
  
  .reading-card {
    background: linear-gradient(135deg, #ffffff 0%, #f7fafc 100%);
    border-radius: 16px; padding: 20px; border: 1px solid #e2e8f0;
    display: flex; gap: 20px; align-items: center; margin-bottom: 30px;
  }
</style>

<div class="main-content">
  <div class="sidebar">
    <h2 style="margin-top:0;">Ymqian</h2>
    <p style="color: #718096; font-size: 0.9em;">终身学习者 | Lifelong Learner</p>
    <hr>
    <nav>
      <ul style="list-style: none; padding: 0; line-height: 2;">
        <li><a href="./">🏠 首页 Home</a></li>
        <li><a href="./goals.html">🎯 年度目标 Goals</a></li>
        <li><a href="./architecture.html">📊 体系架构 System</a></li>
        <li><a href="./library.html">📚 读书分享 Library</a></li>
        <li><a href="./about.html">🙋 关于我 About</a></li>
      </ul>
    </nav>
  </div>

  <div class="content-area">
    
    <section>
      <h3 style="border:none;">📖 正在阅读 Reading Now</h3>
      <div class="reading-card">
        <div style="width: 80px; height: 110px; background: #cbd5e0; border-radius: 4px; display: flex; align-items: center; justify-content: center; font-size: 10px; text-align: center; color: #4a5568;">Book Cover</div>
        <div>
          <h4 style="margin:0;">《高级宏观经济学》</h4>
          <p style="font-size: 0.85em; color: #4a5568; margin: 5px 0;">David Romer | 攻克 UIBE 考博核心教材</p>
          <div style="background: #edf2f7; border-radius: 10px; height: 6px; width: 200px; margin-top: 10px;">
            <div style="background: #4299e1; height: 6px; width: 15%; border-radius: 10px;"></div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h3 style="border:none;">📅 2026 战略路线图</h3>
      </section>

    <section>
      <h3 style="border:none;">🏗️ 体系架构 System Architecture</h3>
      </section>

  </div>
</div>
