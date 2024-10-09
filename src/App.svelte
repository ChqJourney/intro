<script>
  // 不再需要手动切换模式的逻辑
</script>

<div class="app-container">
  <header class="header">
    <div class="logo">Cells</div>
    <nav class="nav">
      <a href="#">Help</a>
    </nav>
  </header>
  <main class="main-content">
    <section class="hero">
      <div class="hero-content">
        <h1>Not just a tool app, it is a new way to handle your report.</h1>
        <p>Cells is a tool chain or platform to help you reporting faster and easier.</p>
        <button class="cta-button">Start</button>
      </div>
    </section>
    <!-- 其他内容 -->
  </main>
  <footer class="footer">
    <p>© 2024 Cells. All rights reserved.</p>
  </footer>
</div>

<style>
  /* 样式将在 app.css 中详细定义 */
  .hero {
    position: relative;
    overflow: hidden;
  }

  .hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: url('blank.jpg');
    background-size: cover;
    background-position: center;
    opacity: 0.3;
    transform: scale(1.1) rotate(2deg);
    z-index: -1;
  }

  .hero-content {
    position: relative;
    z-index: 1;
    /* 添加适当的内边距和其他样式 */
    padding: 2rem;
  }
</style>
