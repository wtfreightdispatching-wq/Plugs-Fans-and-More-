<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Reliable Electrical Services</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      color: #1f2933;
    }
    header {
      background: #0f172a;
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 { font-size: 42px; margin-bottom: 10px; }
    header p { font-size: 18px; margin-bottom: 20px; }
    .cta-btn {
      background: #facc15;
      color: #000;
      padding: 14px 28px;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 24px;
    }
    .card {
      border: 1px solid #e5e7eb;
      border-radius: 10px;
      padding: 24px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    .card h3 { margin-bottom: 10px; }
    .why {
      background: #f8fafc;
    }
    .contact {
      background: #0f172a;
      color: #fff;
      text-align: center;
    }
    .contact a { color: #facc15; font-weight: bold; text-decoration: none; }
    footer {
      background: #020617;
      color: #94a3b8;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <div style="display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap;">
      <div>
        <h1>Plugs Fans and More</h1>
        <p>Residential Electrical Services • Reliable • Affordable</p>
      </div>
      <a href="tel:12095315435" class="desktop-call">📞 Call Now: (209) 531-5435</a>
    </div>
  </header>

  <style>
    .desktop-call {
      display: none;
      background: #16a34a;
      color: #fff;
      padding: 12px 20px;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    @media (min-width: 769px) {
      .desktop-call {
        display: inline-block;
      }
    }
  </style>

  <!-- SERVICES -->
  <section>
    <section>
    <h2>Our Residential Services</h2>
    <br />
    <div class="services">
      <div class="card">
        <h3>Ceiling Fans</h3>
        <p>Installation and replacement of ceiling fans and light fixtures.</p>
      </div>
      <div class="card">
        <h3>Outlets & Switches</h3>
        <p>Replacing outlets, switches, dimmers, and faceplates.</p>
      </div>
      <div class="card">
        <h3>Lighting Upgrades</h3>
        <p>Indoor and outdoor lighting upgrades, including LED fixtures.</p>
      </div>
      <div class="card">
        <h3>Electrical Repairs</h3>
        <p>Troubleshooting and repairs for common residential electrical issues.</p>
      </div>
    </div>
  </section>

  <!-- WHY CHOOSE US -->
  <section class="why">
    <h2>Why Choose Us</h2>
    <br />
    <ul>
      <li>✔ Reliable & Affordable Service</li>
      <li>✔ Honest Pricing & Free Estimates</li>
      <li>✔ On-Time & Professional Work</li>
      <li>✔ Customer Satisfaction Focused</li>
    </ul>
    <p style="margin-top:16px; font-size:14px; color:#475569;">
      *Services limited to non-licensed electrical work where permitted by California law.
    </p>
  </section>

  <!-- CONTACT -->
  <section class="contact" id="contact">
    <h2>Get in Touch</h2>
    <p>Call or text us today to schedule service</p>
    <br />
    <p>📞 <a href="tel:12095315435">(209) 531-5435</a></p>
    <p>📧 <a href="mailto:plugsfansnmore@gmail.com">plugsfansnmore@gmail.com</a></p>
    <p>📍 Serving Modesto, Ceres, Turlock, Livingston, Atwater, Merced, Riverbank, Oakdale, Escalon, Ripon, Manteca & Stockton, California (95350 and surrounding areas)</p>
  </section>

  <footer>
    © 2025 Plugs Fans and More • All Rights Reserved
  </footer>

  <!-- MOBILE CALL NOW BUTTON -->
  <a href="tel:12095315435" class="call-now">📞 Call Now</a>

  <style>
    .call-now {
      display: none;
    }
    @media (max-width: 768px) {
      .call-now {
        display: block;
        position: fixed;
        bottom: 20px;
        left: 50%;
        transform: translateX(-50%);
        background: #16a34a;
        color: #fff;
        padding: 16px 28px;
        border-radius: 999px;
        font-size: 18px;
        font-weight: bold;
        text-decoration: none;
        box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        z-index: 9999;
      }
    }
  </style>
</body>
</html>
