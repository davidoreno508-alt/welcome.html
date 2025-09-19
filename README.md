# welcome.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Client Dashboard</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #1e1e1e;
      color: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background: #111;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #00d084;
    }
    section {
      padding: 20px;
    }
    .video-box, .tasks, .clients {
      background: #2a2a2a;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    iframe {
      width: 100%;
      height: 250px;
      border-radius: 10px;
      border: none;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      padding: 10px;
      text-align: left;
      border-bottom: 1px solid #444;
    }
    th {
      color: #00d084;
    }
    .status {
      padding: 5px 10px;
      border-radius: 8px;
      font-size: 0.9em;
    }
    .active { background: #007f5f; }
    .onboarding { background: #ff8800; }
    .past { background: #a10000; }
  </style>
</head>
<body>
  <header>
    <h1>Client Dashboard</h1>
  </header>

  <!-- Welcome Video -->
  <section class="video-box">
    <h2>Welcome Video</h2>
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
  </section>

  <!-- Next Steps -->
  <section class="tasks">
    <h2>Next Steps</h2>
    <ul>
      <li>✅ Complete onboarding form</li>
      <li>⬜ Schedule kickoff call</li>
      <li>⬜ Upload brand assets</li>
    </ul>
  </section>

  <!-- Clients Table -->
  <section class="clients">
    <h2>Clients</h2>
    <table>
      <thead>
        <tr>
          <th>Client Name</th>
          <th>Status</th>
          <th>Offer Bought</th>
          <th>Date Started</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Reese’s Cup</td>
          <td><span class="status active">Active</span></td>
          <td>—</td>
          <td>—</td>
        </tr>
        <tr>
          <td>Normatec</td>
          <td><span class="status past">Past Client</span></td>
          <td>—</td>
          <td>—</td>
        </tr>
        <tr>
          <td>Celine</td>
          <td><span class="status onboarding">Onboarding</span></td>
          <td>—</td>
          <td>Nov 4, 2024</td>
        </tr>
        <tr>
          <td>Canyon</td>
          <td><span class="status onboarding">Onboarding</span></td>
          <td>Offer 2</td>
          <td>Oct 1, 2024</td>
        </tr>
        <tr>
          <td>Amazon</td>
          <td><span class="status active">Active</span></td>
          <td>Offer 3</td>
          <td>Sep 15, 2024</td>
        </tr>
        <tr>
          <td>Tesla</td>
          <td><span class="status active">Active</span></td>
          <td>Custom</td>
          <td>Sep 11, 2024</td>
        </tr>
      </tbody>
    </table>
  </section>
</body>
</html>
