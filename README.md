# movie-ticket-UI
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Movie Ticket UI</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #1f1f1f;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .ticket {
      background: #fff;
      width: 350px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
      padding: 20px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .ticket:hover {
      transform: scale(1.03);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.5);
    }

    .ticket-header {
      border-bottom: 2px dashed #888;
      margin-bottom: 15px;
      text-align: center;
    }

    .ticket-header h2 {
      margin: 0;
      font-size: 20px;
    }

    .ticket-body p {
      margin: 8px 0;
      color: #333;
    }

    .barcode {
      margin-top: 15px;
      height: 40px;
      background: repeating-linear-gradient(
        90deg,
        #000,
        #000 2px,
        #fff 2px,
        #fff 4px
      );
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <div class="ticket">
    <div class="ticket-header">
      <h2>🎥 AVENGERS: ENDGAME</h2>
    </div>
    <div class="ticket-body">
      <p><strong>Date:</strong> April 27, 2025</p>
      <p><strong>Time:</strong> 7:30 PM</p>
      <p><strong>Seat:</strong> A12</p>
      <p><strong>Theatre:</strong> PVR Cinemas</p>
    </div>
    <div class="barcode"></div>
  </div>
</body>
</html>
