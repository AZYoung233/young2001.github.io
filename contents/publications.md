<sup>#</sup> denotes co-first authors, † denotes the corresponding author

<style>
   .paper-section {
      display: flex;
      align-items: start;
      gap: 20px;
      margin-bottom: 20px;
    }

   .journal-logo {
      padding: 2px 10px;
      border-radius: 5px 5px 0 0;
      /* 添加最小宽度，可根据实际情况调整 */
      width: 200px; 
      /* 如果想固定宽度，可使用 width 属性 */
      /* width: 150px; */ 
      text-align: center; /* 让文字居中显示 */
    }

   .journal-name {
      color: white;
      font-weight: bold;
    }

   .paper-info {
      flex: 1;
    }

   .paper-title {
      margin-top: 0;
      font-size: 1.5rem;
    }

   .authors,
   .publication-info {
      margin-bottom: 0;
    }

   .action-buttons {
      display: flex;
      gap: 10px;
    }

   .button {
      padding: 2px 5px;
      /* 设置固定高度 */
      height: 30px; 
      /* 让文字垂直居中 */
      line-height: 28px; 
      text-decoration: none;
      border-radius: 3px;
      color: black; /* 设置文字为黑色 */
      border: 1px solid black; /* 添加 1 像素宽的黑色边框 */
    }

   .paper-img {
      max-width: 100%;
      width: 200px; /* 可根据需要调整宽度 */
      height: auto;
      margin-bottom: 10px;
    }

    .aaai-logo {
      background-color: #003973;
    }

   .naacl-logo {
      background-color: #ed1d24;
    }
    .arXiv-logo {
      background-color: #b31b1b;
    }

    /* 添加 hr 样式 */
    hr.separator {
      border: 0;
      border-top: 1px solid #666666; /* 深灰色分隔线 */
      margin: 20px 0;
    }
</style>

<strong><strong>Preprint:</strong></strong> 

<div class="paper-section">
    <div>
      <div class="journal-logo arXiv-logo">
        <span class="journal-name">arXiv</span>
      </div>
      <img src="contents/publication_img/PMQ.png" alt="PMQ" class="paper-img">
    </div>
    <div class="paper-info">
      <h2 class="paper-title">Enhancing Contrastive Learning-based Electrocardiogram Pretrained Model with Patient Memory Queue</h2>
      <p class="authors">
        Xiaoyu Sun<sup>#</sup>,
        <strong>Yang Yang</strong><sup>#</sup>,
        and Xunde Dong†.
         </p>
      <p class="conference-info">
        <strong>In arXiv 2025. This paper was sponsored by the SCUT Student Research Project. </strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://arxiv.org/pdf/2506.06310" class="button">arXiv</a>
      <a href="https://github.com/3hiuwoo/PMQ" class="button">Code</a>
    </div>
  </div>

  <!-- 添加分隔线 -->
  <hr class="separator">

<strong><strong>Conference Papers:</strong></strong>

<!-- 第一篇论文 -->
<div class="paper-section">
    <div>
      <div class="journal-logo aaai-logo">
        <span class="journal-name">AAAI</span>
      </div>
      <img src="contents/publication_img/MSE-Adapter.png" alt="MSE-Adapter" class="paper-img">
    </div>
    <div class="paper-info">
      <h2 class="paper-title">MSE-Adapter: A Lightweight Plugin Endowing LLMs with the Capability to Perform Multimodal Sentiment Analysis and Emotion Recognition</h2>
      <p class="authors">
        <strong>Yang Yang</strong>,
        Xunde Dong†  
        and Yupeng Qiang.
         </p>
      <p class="conference-info">
        <strong>In AAAI 2025</strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/download/34755/36910" class="button">Paper</a>
      <a href="https://arxiv.org/pdf/2502.12478" class="button">arXiv</a>
      <a href="https://github.com/AZYoung233/MSE-Adapter" class="button">Code</a>
    </div>
  </div>

  <!-- 第二篇论文 -->
  <div class="paper-section">
    <div>
      <div class="journal-logo naacl-logo">
        <span class="journal-name">NAACL</span>
      </div>
      <img src="contents/publication_img/CLGSI.png" alt="CLGSI" class="paper-img">
    </div>
    <!-- 这里是绝对路径！特别傻逼 -->
    <div class="paper-info">
      <h2 class="paper-title">CLGSI: A Multimodal Sentiment Analysis Framework based on Contrastive Learning Guided by Sentiment Intensity</h2>
       <p class="authors">
        <strong>Yang Yang</strong>,
        Xunde Dong†  
        and Yupeng Qiang.
      </p>
      <p class="conference-info">
        <strong>In NAACL 2024 Findings</strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://aclanthology.org/2024.findings-naacl.135.pdf" class="button">Paper</a>
      <a href="https://github.com/AZYoung233/CLGSI" class="button">Code</a>
    </div>
  </div>