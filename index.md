<style>
  body {
    background-color: #f7f9fc; /* 清爽的浅蓝灰色背景 */
    color: #2d3748;           /* 深石板灰文字，比纯黑更高级 */
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    max-width: 850px;         /* 限制宽度，防止文字在大屏幕上拉得太长 */
    margin: 0 auto;           /* 页面居中 */
    padding: 40px 20px;       /* 增加边距，留白产生美感 */
  }
  
  /* 美化链接颜色 */
  a {
    color: #3182ce; 
    text-decoration: none;
    border-bottom: 1px solid #ebf8ff;
    transition: all 0.3s;
  }
  
  a:hover {
    color: #2b6cb0;
    border-bottom: 1px solid #3182ce;
  }
</style>

<img src="/banner.jpg" style="width: 100%; border-radius: 12px; margin-bottom: 20px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">

# Be yourself and don't go with the flow.

你好，欢迎来到我的数字空间。我是一名拥有 15 年电气工程背景的**终身学习者**。

这里是我记录思考、沉淀知识的“数字花园”。目前我正专注于**自我提升**、**经济学ph.D**、**AI 自动化工作流**以及的探索。

---
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ 
    startOnLoad: true,
    theme: 'base', // 使用基础主题进行深度定制
    themeVariables: {
      primaryColor: '#e1e8f0',       // 支柱节点背景色（浅蓝灰）
      primaryTextColor: '#2d3748',   // 文字颜色
      primaryBorderColor: '#cbd5e0', // 边框颜色
      lineColor: '#a0aec0',          // 连线颜色
      secondaryColor: '#fbd38d',     // 顶点（TOP）背景色
      tertiaryColor: '#edf2f7',       // 底层基石背景色
      fontSize: '15px',
      fontFamily: '-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif'
    }
  });
</script>

<style>
  /* 2. 为架构图容器添加“Tw93 风格”卡片效果 */
  .architecture-card {
    background: white;
    border-radius: 16px;
    padding: 30px;
    margin: 30px 0;
    border: 1px solid #e2e8f0;
    box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.05);
    overflow-x: auto; /* 保证手机端也能滑动查看 */
    text-align: center;
  }
  
  /* 标题美化 */
  .card-label {
    display: inline-block;
    background: #4a5568;
    color: white;
    padding: 4px 12px;
    border-radius: 20px;
    font-size: 12px;
    margin-bottom: 20px;
    letter-spacing: 1px;
    text-transform: uppercase;
  }
</style>

<div class="architecture-card">
  <div class="card-label">System Architecture</div>
  
  <pre class="mermaid">
graph TD
    %% 顶点
    TOP((<b>体系架构<br/>System Architecture</b>))

    %% 四个支撑支柱
    P1["<b>AI 与电力</b><br/>注册电气考证 / n8n 自动化"]
    P2["<b>阅读与写作</b><br/>雅思 6.5 / 自媒体输出"]
    P3["<b>数学与经济学</b><br/>2027 申博 / 底层逻辑"]
    P4["<b>统计学</b><br/>FRM 备考 / 计量工具"]

    %% 支撑关系
    P1 --- TOP
    P2 --- TOP
    P3 --- TOP
    P4 --- TOP

    %% 底层基石
    BASE["<b>底层基石：终身学习者的自我管理</b><br/>(时间管理 / 情绪调节 / 家庭责任)"]

    BASE -.-> P1
    BASE -.-> P2
    BASE -.-> P3
    BASE -.-> P4

    %% 节点样式（代码内局部覆盖）
    style TOP fill:#ffd382,stroke:#ed8936,stroke-width:3px
    style BASE fill:#f7fafc,stroke:#cbd5e0,stroke-dasharray: 5 5
  </pre>
</div>
