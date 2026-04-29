<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Society</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background: #050505;
      color: #f5f5f5;
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at 20% 30%, rgba(212,175,55,0.12), transparent 40%),
                  radial-gradient(circle at 80% 70%, rgba(255,255,255,0.05), transparent 35%);
      z-index: -1;
    }

    header {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 40px;
      text-align: center;
    }

    header h1 {
      font-size: 4rem;
      font-weight: 700;
      letter-spacing: 3px;
      background: linear-gradient(90deg, #fff, #d4af37);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 20px;
    }

    header p {
      max-width: 700px;
      font-size: 1.2rem;
      color: #cfcfcf;
      margin-bottom: 30px;
    }

    .btn {
      padding: 14px 32px;
      border: 1px solid #d4af37;
      border-radius: 50px;
      color: #d4af37;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s ease;
      backdrop-filter: blur(8px);
    }

    .btn:hover {
      background: #d4af37;
      color: #050505;
      box-shadow: 0 0 20px rgba(212,175,55,0.5);
    }

    section {
      padding: 100px 20px;
      text-align: center;
    }

    h2 {
      font-size: 2.8rem;
      margin-bottom: 20px;
      color: #d4af37;
    }

    .pricing {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 50px;
    }

    .card {
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(212,175,55,0.25);
      border-radius: 20px;
      padding: 35px;
      width: 320px;
      backdrop-filter: blur(14px);
      transition: 0.4s ease;
      box-shadow: 0 10px 40px rgba(0,0,0,0.35);
    }

    .card:hover {
      transform: translateY(-12px);
      border-color: #d4af37;
      box-shadow: 0 0 25px rgba(212,175,55,0.35);
    }

    .card h3 {
      font-size: 1.5rem;
      margin-bottom: 15px;
    }

    .price {
      font-size: 2.5rem;
      font-weight: bold;
      color: #fff;
      margin: 15px 0;
    }

    .tag {
      display: inline-block;
      padding: 6px 14px;
      border: 1px solid #d4af37;
      border-radius: 30px;
      font-size: 0.9rem;
      margin-bottom: 15px;
      color: #d4af37;
    }

    footer {
      padding: 40px;
      text-align: center;
      border-top: 1px solid rgba(255,255,255,0.08);
      color: #999;
    }

    footer a {
      color: #d4af37;
      text-decoration: none;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.8rem;
      }

      .pricing {
        flex-direction: column;
        align-items: center;
      }
    }
  
    .platform-bar {
      width: 100%;
      padding: 18px;
      text-align: center;
      font-weight: 600;
      letter-spacing: 2px;
      color: #fff;
      background: #0a0a0a;
      border-bottom: 1px solid rgba(212,175,55,0.4);
      position: relative;
      overflow: hidden;
    }

</style>
</head>
<body>

  <div class="platform-bar">SOCIETY PLATFORM</div>

  

  <header>
    <h1>SOCIETY</h1>
    <p>
      Luxury-inspired, high-converting websites designed with a futuristic edge.
      Elevate your business with sleek digital experiences.
    </p>
    <a href="https://www.linkedin.com/in/renan-ayres-de-carvalho-b1a2593a6?utm_source=share_via&utm_content=profile&utm_medium=member_ios" target="_blank" class="btn">
      Connect on LinkedIn
    </a>
  </header>

  <section>
    <h2>Website Packages</h2>
    <div class="pricing">

      <div class="card" style="cursor:pointer" onclick="navigator.clipboard.writeText('Hi! I am interested in the $175 Starter website. What would you like me to include in your project?'); window.open('https://www.linkedin.com/messaging/','_blank')">
        <span class="tag">Starter</span>
        <h3>Simple One-Page Website</h3>
        <div class="price">$175</div>
        <p>Elegant, responsive, and perfect for portfolios or small businesses.</p>
      </div>

      <div class="card" style="cursor:pointer" onclick="navigator.clipboard.writeText('Hi! I am interested in the $250 Premium website. What advanced features would you like included?'); window.open('https://www.linkedin.com/messaging/','_blank')">
        <span class="tag">Premium</span>
        <h3>Better Quality Website</h3>
        <div class="price">$250</div>
        <p>Enhanced visuals, polished structure, and a stronger online presence.</p>
      </div>
        

    </div>
  </section>

  <section>
    <h2>Why Work With Me?</h2>
    <p>
      I combine modern technology with luxury aesthetics to create websites that stand out.
      My mission is to deliver affordable excellence with premium appeal.
    </p>
  </section>

  <footer>
    <p>© 2026 Society | Contact via
      <a href="https://www.linkedin.com/in/renan-ayres-de-carvalho-b1a2593a6?utm_source=share_via&utm_content=profile&utm_medium=member_ios">
        LinkedIn
      </a>
    </p>
  </footer>

</body>
</html>
