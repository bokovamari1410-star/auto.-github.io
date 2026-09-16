<!DOCTYPE html>.
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Автоаксессуары — тюнинг-декор для авто</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500;600;700&family=Inter:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #14161a;
    --bg-alt: #1b1e24;
    --line: #2b2f37;
    --text: #edeef0;
    --text-dim: #9aa1ac;
    --accent: #6ec8ff;
  }
  *{ box-sizing: border-box; }
  html,body{ margin:0; padding:0; }
  body{
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', system-ui, sans-serif;
    line-height: 1.55;
    -webkit-font-smoothing: antialiased;
  }
  .wrap{
    max-width: 720px;
    margin: 0 auto;
    padding: 88px 24px 64px;
  }
  .mark{
    display:flex;
    align-items:center;
    gap:10px;
    margin-bottom: 56px;
  }
  .mark .dot{
    width: 10px; height: 10px;
    border-radius: 50%;
    background: var(--accent);
    box-shadow: 0 0 14px 2px var(--accent);
  }
  .mark span{
    font-family:'Oswald', sans-serif;
    font-weight: 600;
    font-size: 15px;
    letter-spacing: 0.02em;
    color: var(--text-dim);
  }
  h1{
    font-family: 'Oswald', sans-serif;
    font-weight: 700;
    font-size: clamp(34px, 6vw, 52px);
    line-height: 1.08;
    margin: 0 0 22px;
    max-width: 14ch;
  }
  h1 em{
    font-style: normal;
    color: var(--accent);
  }
  p.lead{
    font-size: 18px;
    color: var(--text-dim);
    max-width: 46ch;
    margin: 0 0 48px;
  }
  .divider{
    height: 1px;
    background: var(--line);
    margin: 0 0 40px;
  }
  h2{
    font-family: 'Oswald', sans-serif;
    font-weight: 600;
    font-size: 13px;
    letter-spacing: 0.03em;
    color: var(--text-dim);
    margin: 0 0 20px;
  }
  ul.items{
    list-style: none;
    margin: 0 0 48px;
    padding: 0;
    border-top: 1px solid var(--line);
  }
  ul.items li{
    display:flex;
    justify-content: space-between;
    align-items: baseline;
    padding: 16px 0;
    border-bottom: 1px solid var(--line);
    font-size: 16px;
  }
  ul.items li .n{
    color: var(--text);
  }
  ul.items li .d{
    color: var(--text-dim);
    font-size: 14px;
    text-align: right;
  }
  .contact{
    background: var(--bg-alt);
    border: 1px solid var(--line);
    border-radius: 4px;
    padding: 28px;
  }
  .contact p{
    margin: 0 0 16px;
    color: var(--text-dim);
    font-size: 15px;
  }
  .contact a{
    color: var(--accent);
    text-decoration: none;
    font-weight: 500;
    border-bottom: 1px solid rgba(110,200,255,0.35);
  }
  .contact a:hover{ border-bottom-color: var(--accent); }
  footer{
    margin-top: 56px;
    font-size: 13px;
    color: var(--text-dim);
    opacity: 0.7;
  }
  @media (prefers-reduced-motion: no-preference){
    .wrap{ animation: rise 0.5s ease-out; }
    @keyframes rise{
      from{ opacity: 0; transform: translateY(8px); }
      to{ opacity: 1; transform: translateY(0); }
    }
  }
</style>
</head>
<body>
  <div class="wrap">
    <div class="mark">
      <div class="dot"></div>
      <span>АВТОДЕКОР</span>
    </div>

    <h1>Внешний тюнинг&nbsp;и <em>световой декор</em> для авто</h1>
    <p class="lead">Небольшой магазин с продажей и установкой внешних аксессуаров: ДХО, спойлеры, накладки и диффузоры. Работаем через Avito.</p>

    <div class="divider"></div>

    <h2>ЧТО В НАЛИЧИИ</h2>
    <ul class="items">
      <li><span class="n">Дневные ходовые огни (ДХО)</span><span class="d">от 3 линз</span></li>
      <li><span class="n">Спойлеры</span><span class="d">разных размеров</span></li>
      <li><span class="n">Диффузоры бампера</span><span class="d">под конкретную модель</span></li>
      <li><span class="n">Подсветка багажника</span><span class="d">LED</span></li>
      <li><span class="n">Накладки на капот и вставки</span><span class="d">под заказ</span></li>
    </ul>

    <div class="contact">
      <p>Все актуальные объявления и цены — на Avito.</p>
      <a href="https://www.avito.ru/brands/e2ff38b92bfa9978d3ee00df197bf24e?src=sharing">Смотреть на Avito →</a>
    </div>

    <footer>© 2026 Автодекор</footer>
  </div>
</body>
</html>
