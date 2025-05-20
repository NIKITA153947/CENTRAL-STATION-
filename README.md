<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Central Station - Professional Fire Alarm Services for Installation, Maintenance, and Notifications" />
  <meta name="keywords" content="fire alarm, service call, fire alarm installation, fire safety, central station" />
  <meta name="author" content="Central Station" />
  <title>Central Station | Fire Alarm Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #cc0000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
    }
    nav a {
      color: #fff;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #575757;
    }
    .container {
      padding: 20px;
    }
    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 10px;
    }
    .email-column {
      margin-top: 30px;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
    }
    .service, .notification {
      border: 1px solid #ddd;
      padding: 10px;
      margin: 10px 0;
      border-left: 6px solid;
    }
    .service { border-color: #cc0000; }
    .notification { border-color: #00cc66; }
    .private-section {
      display: none;
    }
    .borough-section {
      margin-top: 40px;
    }
    .borough-section h3 {
      background-color: #cc0000;
      color: white;
      padding: 10px;
      border-radius: 4px;
    }
    .borough-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }
    .testing, .not-testing {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .testing {
      background-color: #e6f7ff;
    }
    .not-testing {
      background-color: #fff0f0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Central Station</h1>
    <p>Reliable Fire Alarm Installation, Inspection & Service Calls</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="home">
      <h2>Welcome</h2>
      <p>Central Station specializes in fire alarm installation, inspection, and emergency service calls.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Fire Alarm Installation</li>
        <li>Monthly and Annual Inspections</li>
        <li>Emergency Service Calls</li>
        <li>Violation Corrections</li>
      </ul>
    </section>

    <section class="borough-section">
      <h2>Service Areas by Borough</h2>

      <div>
        <h3>Brooklyn</h3>
        <div class="borough-grid">
          <div class="testing">
            <strong>Testing:</strong>
            <ul>
              <li>451 Fulton Street - Smoke Detector Testing</li>
            </ul>
          </div>
          <div class="not-testing">
            <strong>Not Testing:</strong>
            <ul>
              <li>805 Rockaway Parkway - Awaiting Inspection</li>
            </ul>
          </div>
        </div>
      </div>

      <div>
        <h3>Bronx</h3>
        <div class="borough-grid">
          <div class="testing">
            <strong>Testing:</strong>
            <ul>
              <li>545 E 144th Street - Annual Fire Panel Test</li>
            </ul>
          </div>
          <div class="not-testing">
            <strong>Not Testing:</strong>
            <ul>
              <li>443 St. Ann Avenue - Panel Not Accessible</li>
            </ul>
          </div>
        </div>
      </div>

      <div>
        <h3>Manhattan</h3>
        <div class="borough-grid">
          <div class="testing">
            <strong>Testing:</strong>
            <ul>
              <li>99 Madison Avenue - Monthly Inspection</li>
            </ul>
          </div>
          <div class="not-testing">
            <strong>Not Testing:</strong>
            <ul>
              <li>31 East 32nd Street - Violation Notice Pending</li>
            </ul>
          </div>
        </div>
      </div>

      <div>
        <h3>Queens</h3>
        <div class="borough-grid">
          <div class="testing">
            <strong>Testing:</strong>
            <ul>
              <li>110 Scott Avenue - Alarm Reset Tested</li>
            </ul>
          </div>
          <div class="not-testing">
            <strong>Not Testing:</strong>
            <ul>
              <li>35 Commercial Street - Not Yet Scheduled</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="email-column" class="email-column private-section">
      <h2>Private Email Analysis</h2>
      <div class="service">
        <strong>Service Call Required:</strong> Smoke detector not functioning at 451 Fulton Street.
      </div>
      <div class="notification">
        <strong>Notification:</strong> Monthly inspection due at 99 Madison Avenue.
      </div>
      <div class="notification">
        <strong>Notification:</strong> Alarm panel reset successfully at 110 Scott Avenue.
      </div>
      <p><em>This section is private and requires login access.</em></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Central Station. All rights reserved.</p>
  </footer>
</body>
</html>
