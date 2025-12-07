<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>The Pie-nt Size Cookie Co.</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="The Pie-nt Size Cookie Co. bakes cookie-sized pies with cozy, nostalgic flavor—small batch, big heart." />

  <style>
    :root{
      --brown:#4a3422;
      --tan:#f3e2c3;
      --cream:#fff7e7;
      --accent:#c18438;
      --max-width:1100px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
      background:var(--cream);
      color:var(--brown);
      line-height:1.6;
    }

    /* Navigation */
    .site-nav{
      position:sticky;
      top:0;
      background:rgba(255,247,231,0.95);
      border-bottom:1px solid rgba(0,0,0,.08);
      z-index:1000;
    }
    .nav-inner{
      max-width:var(--max-width);
      margin:0 auto;
      padding:0.75rem 1.5rem;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }
    .logo{
      font-weight:700;
      letter-spacing:.08em;
      font-size:.85rem;
    }
    .nav-links a{
      text-decoration:none;
      color:var(--brown);
      font-size:.7rem;
      letter-spacing:.18em;
      text-transform:uppercase;
      margin-left:1rem;
    }

    header, section{
      max-width:var(--max-width);
      margin:0 auto;
      padding:3rem 1.5rem;
    }

    footer{
      text-align:center;
      padding:2rem 1.5rem;
      font-size:.85rem;
      opacity:.8;
    }

    @media(max-width:800px){
      .visit-grid{grid-template-columns:1fr}
      .nav-links{display:none}
      .sustain-grid{grid-template-columns:1fr}
    }
  
    /* Sustainability grid */
    .sustain-grid{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:2rem;
      margin-top:1.5rem;
    }
    .sustain-card{
      background:#fffaf0;
      padding:1.75rem;
      border-radius:18px;
      border:1px solid rgba(0,0,0,0.06);
      position:relative;
    }
    
    /* Bee + Whisk subtle differentiation */
    .sustain-card:first-child{
      background:linear-gradient(180deg,#fffaf0 0%, #fff3cf 100%);
    }
    .sustain-card:first-child::before{
      content:"🐝";
      position:absolute;
      top:1rem;
      right:1rem;
      font-size:1.2rem;
      opacity:0.35;
    }
    .sustain-card:last-child{
      background:linear-gradient(180deg,#fffaf0 0%, #f3e7da 100%);
    }
    .sustain-card:last-child::before{
      content:"🥣";
      position:absolute;
      top:1rem;
      right:1rem;
      font-size:1.2rem;
      opacity:0.35;
    }

    /* Merch logo badge */
    .logo-badge{
      display:flex;
      align-items:center;
      justify-content:center;
      background:var(--cream);
      border:2px solid rgba(74,52,34,0.15);
      border-radius:999px;
      padding:2rem 1.25rem;
    }
    .logo-badge img{
      max-width:180px;
      width:100%;
      height:auto;
    }


    /* Hero layout */
    .hero-grid{
      display:grid;
      grid-template-columns:1.1fr 0.9fr;
      gap:2.5rem;
      align-items:center;
    }
    .hero-cta{margin-top:1.25rem}
    .btn{
      display:inline-block;
      margin-right:.75rem;
      padding:.65rem 1.4rem;
      border-radius:999px;
      border:2px solid var(--brown);
      background:var(--brown);
      color:var(--cream);
      text-decoration:none;
      font-size:.75rem;
      letter-spacing:.12em;
      text-transform:uppercase;
    }
    .btn.secondary{background:transparent;color:var(--brown)}

    /* Menu */
    .menu-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
      gap:1.5rem;
      margin-top:1.5rem;
    }
    .menu-item{
      background:#fffaf0;
      padding:1.5rem;
      border-radius:18px;
    }
    .menu-meta{display:flex;justify-content:space-between;font-size:.8rem;margin-top:.75rem}
    .menu-tagline{font-size:.85rem;opacity:.75;margin-top:.75rem}

    /* Reviews */
    .reviews-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
      gap:1.25rem;
      margin-top:1.5rem;
    }
    .review-card{background:#fffaf0;padding:1.25rem;border-radius:16px}
    .review-name{margin-top:.5rem;font-weight:600;font-size:.85rem}
    .review-note{margin-top:1rem;font-size:.85rem;opacity:.75}

    /* Visit */
    .visit-grid{display:grid;grid-template-columns:1.2fr 0.8fr;gap:2rem;margin-top:1.5rem}
    .hours-list{list-style:none;padding:0;margin:1rem 0}
    .hours-list li{display:grid;grid-template-columns:1fr auto;padding:.5rem 0;border-bottom:1px dashed rgba(0,0,0,.15)}
    .hours-list li:last-child{border-bottom:none}
    .contact-card{
      background:#fffaf0;
      padding:1.75rem 1.75rem 1.9rem;
      border-radius:18px;
    }
    .contact-card h3{
      margin-top:0;
    }
    .contact-card p{
      margin:0.6rem 0 1rem;
    }
    .contact-card form{
      display:flex;
      flex-direction:column;
      gap:0.75rem;
    }
    .contact-card input{
      width:100%;
      padding:.6rem .75rem;
      border-radius:999px;
      border:1px solid rgba(0,0,0,.2);
    }
    .contact-card button{
      align-self:flex-start;
    }
    .contact-card form p{
      margin:0.4rem 0 0;
      font-size:0.75rem;
      opacity:0.75;
    }

    @media(max-width:900px){.hero-grid{grid-template-columns:1fr}.hero-image{order:-1}}

</style>
</head>
<body>

<nav class="site-nav">
  <div class="nav-inner">
    <span class="logo">THE PIE-NT SIZE COOKIE CO.</span>
    <div class="nav-links">
      <a href="#about">Story</a>
      <a href="#mission">Mission</a>
      <a href="#menu">Menu</a>
      <a href="#sustainability">Sustainability</a>
      <a href="#reviews">Reviews</a>
      <a href="#visit">Visit</a>
    </div>
  </div>
</nav>

<header class="hero">
  <div class="hero-grid">
    <div class="hero-text">
      <h1>Cookie-sized pies. Big comfort.</h1>
      <p>
        The Pie-nt Size Cookie Co. bakes cookie-sized pies that deliver all the cozy, nostalgic flavors
        of classic desserts in a grab-n-go bite. Small batch, big heart, and made to be shared (or not shared at all).
      </p>
      <div class="hero-cta">
        <a class="btn" href="#menu">See Today’s Flavors</a>
        <a class="btn secondary" href="#visit">Plan a Visit</a>
      </div>
      
    </div>
    <div class="hero-image">
      <img src="assets/hero-cookie.png" alt="Banana Cream Pie Cookie" style="width:100%;max-width:420px;border-radius:24px;display:block;margin:0 auto;" />
      <p style="margin-top:.75rem;font-size:.8rem;opacity:.8;text-align:center;">Banana Cream Pie Cookie – fan favorite &amp; our first recipe!</p>
    </div>
  </div>
</header>

<section id="about">
  <div class="section-tag">Our Story</div>
  <h2>Dessert That Feels Like Home</h2>
  <p>
    The Pie-nt Size Cookie Co. started with one simple question: what if your favorite slice of pie could fit in the palm of your hand?
    Our cookie-sized pies are crafted to offer a nostalgic yet novel dessert experience — something that feels both familiar and brand new.
    We believe dessert should be inclusive, comforting, and rooted in real ingredients.
  </p>
  <p>
    We believe dessert should feel personal. That’s why we bake in small batches, use quality ingredients, and offer options
    for a wide range of dietary needs. Whether you’re here for a quick treat, a thoughtful gift, or a new family tradition,
    there’s a Pie-nt Size cookie waiting for you.
  </p>
</section>

<section id="mission">
  <div class="section-tag">Our Mission</div>
  <h2>Small Desserts. Big Comfort.</h2>
  <p>
    Our mission is to reimagine classic desserts in a way that’s joyful, approachable, and made with care.
    We believe food connects people — sparking memories, starting traditions, and turning everyday moments into something special.
  </p>
</section>

<section id="menu">
  <div class="section-tag">Signature Lineup</div>
  <h2>Cookie-sized pies you’ll dream about</h2>

  <div class="menu-grid">
    <article class="menu-item">
      <h3>Banana Cream Pie</h3>
      <p>A buttery short-bread “crust” topped with banana pudding, fresh banana slices, Swiss meringue, and vanilla wafer crumbs.</p>
      <div class="menu-meta"><span>$5.00</span><span>Fan favorite</span></div>
      <p class="menu-tagline">Our very first recipe — and still the most talked about.</p>
    </article>

    <article class="menu-item">
      <h3>Pumpkin Pie</h3>
      <p>All the cozy spice of pumpkin pie baked into a soft cookie with whipped cream and a sprinkle of pumpkin spice.</p>
      <div class="menu-meta"><span>$5.00</span><span>Seasonal</span></div>
      <p class="menu-tagline">Perfect with a sweater and a good book.</p>
    </article>

    <article class="menu-item">
      <h3>Key Lime Pie</h3>
      <p>Zesty lime curd layered on our classic short-bread “crust” and topped with a fluffy dollop of Swiss meringue.</p>
      <div class="menu-meta"><span>$5.00</span><span>Spring & Summer</span></div>
      <p class="menu-tagline">Bright, tart, and refreshing.</p>
        </article>

    <article class="menu-item">
      <h3>Gluten-free Chocolate Chip</h3>
      <p>A gluten-free take on a classic favorite, baked soft with rich chocolate chips and finished with a pinch of flaky sea salt.</p>
      <div class="menu-meta"><span>$5.00</span><span>Gluten-free</span></div>
      <p class="menu-tagline">Comforting, classic, and made for everyone.</p>
    </article>

    <article class="menu-item">
      <h3>Mississippi Mud Pie</h3>
      <p>A decadent chocolate chocolate chip short-bread “crust” layered with chocolate pudding, a swirl of whipped cream, and topped with chocolate shavings.</p>
      <div class="menu-meta"><span>$5.00</span><span>Rich &amp; indulgent</span></div>
      <p class="menu-tagline">For serious chocolate lovers only.</p>
    </article>

    <article class="menu-item">
      <h3>Cherry Pie</h3>
      <p>A buttery short-bread “crust” topped with tart cherry filling and finished with crunchy streusel.</p>
      <div class="menu-meta"><span>$5.00</span><span>Seasonal</span></div>
      <p class="menu-tagline">Sweet, tart, and delightfully nostalgic.</p>
    </article>
  </div>
</section>

<section id="sustainability">
  <div class="section-tag">Good For You &amp; The Planet</div>
  <h2>Thoughtful baking, inside and out</h2>

  <div class="sustain-grid">
    <div class="sustain-card">
      <h3>Eco‑Conscious Packaging</h3>
      <p>
        Our boxes are compostable and embedded with flower seeds, so when you're done with your treats,
        you can plant a little beauty for local bees. It’s our way of turning dessert into a small act of care.
      </p>
      <p>
        We prioritize minimal plastics, small-batch baking to reduce waste, and sustainable partners whenever possible.
      </p>
    </div>

    <div class="sustain-card">
      <h3>Take-n-Make Kits</h3>
      <p>
        Want to bring the Pie-nt Size experience home? Our take-n-make cookie kits include our signature pre-baked short-bread "crust",
        toppings, and easy instructions so you can make fresh pie cookies in your own kitchen.
      </p>
      <p>
        Kits are perfect for family nights, parties, or gifting — and they cut down on waste by letting you make only what you need.
      </p>
    </div>
  </div>
</section>

<section id="merch">
  <div class="section-tag">Merch</div>
  <h2>Wear the Pie-nt Size Love</h2>
  <p>Join the Pie-nt Size family and strut your stuff in our cozy merch.</p>

  <div class="menu-grid">
    <div class="menu-item">
      <img src="assets/Pie-nt size hat merch.png" alt="Pie-nt Size Dad Hat" style="width:100%;border-radius:14px;margin-bottom:0.75rem;" />
    </div>
    <div class="menu-item logo-badge">
  <img src="assets/Logo and words.png" alt="Pie-nt Size Classic Logo" />
</div>
    <div class="menu-item">
      <img src="assets/Pie-nt Size Hoodie merch.png" alt="Pie-nt Size Hoodie" style="width:100%;border-radius:14px;margin-bottom:0.75rem;" />
    </div>
  </div>
</section>

<section id="reviews">
  <div class="section-tag">What People Are Saying</div>
  <h2>Real Customers. Real Obsessions.</h2>
  <p>We could talk about these cookies all day, but we’ll let our guests do it instead.</p>

  <div class="reviews-grid">
    <div class="review-card"><p>“Those Pumpkin Pie Cookies are the bomb. I can't stop thinking about them.”</p><div class="review-name">– Danielle K.</div></div>
    <div class="review-card"><p>“Seriously soooo good… maybe too good :)”</p><div class="review-name">– Stephen A.</div></div>
    <div class="review-card"><p>“The Banana cream is on the same level as Crumbl cookies.”</p><div class="review-name">– Bahne K.</div></div>
    <div class="review-card"><p>“Very good cookies! The flavor is fantastic and short-bread cookie is a great way to mimic a pie crust."</p><div class="review-name">– Gavin L.</div></div>
    <div class="review-card"><p>“The banana cream pie cookie is probably in the top 3 desserts I've ever had. 100% I'd buy that every time I could.”</p><div class="review-name">– Douglas L.</div></div>
    <div class="review-card"><p>“The flavors were awesome buy my favorite part was the texture. It was the perfect chewy, soft cookie that you would buy from a really good bakery. 10/10 would eat again.”</p><div class="review-name">– Haley F.</div></div>
  </div>

  <p class="review-note">Psst… we love hearing your thoughts. Tag us on social with your favorite flavor and #pientsizecookieco.</p>
</section>

<section id="visit">
  <div class="section-tag">Visit Us</div>
  <h2>Come grab a Pie-nt Size treat</h2>

  <div class="visit-grid">
    <div>
      <p>
        Our first storefront is rooted in the Fargo–Moorhead community and is meant to feel like walking into your family's kitchen —
        warm, welcoming, and always filled with something delicious in the oven.
      </p>
      <h3>Hours</h3>
      <ul class="hours-list">
        <li><span>Mon – Thu</span><span>8:00am – 6:00pm</span></li>
        <li><span>Friday</span><span>8:00am – 8:00pm</span></li>
        <li><span>Saturday</span><span>9:00am – 8:00pm</span></li>
        <li><span>Sunday</span><span>Closed (family + recipe testing day!)</span></li>
      </ul>
    </div>

    <div class="contact-card">
      <h3>Stay in the Cookie Loop</h3>
      <p>Want first dibs on new flavors, holiday boxes, and limited-run kits? Join our email list and we'll send only the good stuff - no spam, just crumbs.</p>
      <form>
        <input type="email" placeholder="hello@pientsizecookies.com" required style="width:100%;padding:.5rem;border-radius:999px;border:1px solid rgba(0,0,0,.2);" />
        <button class="btn" type="submit">GET FLAVOR UPDATES</button>
        <p style="margin-top:0.6rem;font-size:0.75rem;opacity:0.75;">Or send us a note at <a href="mailto:hello@pientsizecookies.com">hello@pientsizecookies.com</a> for catering, custom boxes, or submitting ideas.</p>
      </form>
    </div>
  </div>
</section>

<footer>
  © <span id="year"></span> The Pie-nt Size Cookie Co. – Cookie-sized pies, huge personality
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
