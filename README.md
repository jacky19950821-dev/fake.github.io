<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Product Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f8f8f8;
      color: #333;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    .product-section {
      padding: 1rem;
      background: #fff;
      text-align: center;
    }
    .product-section img {
      max-width: 100%;
      height: auto;
      border-radius: 12px;
    }
    .product-description {
      margin-top: 1rem;
      font-size: 1rem;
    }
    .contact-button {
      display: block;
      width: 80%;
      max-width: 300px;
      margin: 2rem auto;
      padding: 0.75rem;
      background-color: #ff0050;
      color: #fff;
      border: none;
      border-radius: 8px;
      font-size: 1.1rem;
      text-align: center;
      text-decoration: none;
    }
    .reviews-section {
      background-color: #f0f0f0;
      padding: 1.5rem 1rem;
    }
    .review {
      background: #fff;
      border-radius: 8px;
      padding: 1rem;
      margin-bottom: 1rem;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    .review h4 {
      margin: 0 0 0.5rem 0;
    }
    .review p {
      margin: 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>🔥 热卖产品：智能宠物喂食器</h1>
  </header>

  <section class="product-section">
    <img src="https://via.placeholder.com/600x400?text=Pet+Feeder+Image" alt="Smart Pet Feeder" />
    <div class="product-description">
      <h2>智能宠物喂食器</h2>
      <p>远程控制 | 定时投食 | 大容量储粮 | 语音互动<br/>
      让你无论身处何地，也能轻松照顾爱宠！</p>
    </div>
  </section>

  <a class="contact-button" href="https://wa.me/1234567890" target="_blank">📩 联系我们</a>

  <section class="reviews-section">
    <h2 style="text-align: center;">✨ 客户评价</h2>

    <div class="review">
      <h4>🐶 Alice, 美国</h4>
      <p>产品太棒了！出差期间也能给狗狗喂食，超级方便。</p>
    </div>

    <div class="review">
      <h4>🐱 Jack, 英国</h4>
      <p>使用简单，APP操作顺滑，猫咪很喜欢这个设备！</p>
    </div>

    <div class="review">
      <h4>🐾 Emma, 德国</h4>
      <p>物流快，客服也很专业，非常满意的一次购物体验。</p>
    </div>
  </section>

</body>
</html>
