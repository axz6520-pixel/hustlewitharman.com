<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WORK FORM HOME</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff;
      color: #111;
      text-align: center;
    }
    header {
      padding: 15px;
      font-size: 28px;
      font-weight: bold;
      background: #fff;
      border-bottom: 2px solid #eee;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .profile {
      margin: 30px auto 15px;
    }
    .profile img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #25D366;
      transition: transform 0.4s ease;
    }
    .profile img:hover {
      transform: scale(1.05);
    }
    h2 {
      margin: 15px 0;
      font-size: 22px;
      font-weight: bold;
    }
    /* WhatsApp main button */
    .btn {
      display: inline-block;
      margin: 20px auto;
      padding: 15px 40px;
      font-size: 1.2rem;
      font-weight: bold;
      color: #fff;
      background: #25D366;
      border-radius: 50px;
      text-decoration: none;
      position: relative;
      overflow: hidden;
      border: 2px dashed red;
      transition: transform 0.3s ease, background 0.3s ease;
    }
    .btn:hover {
      background: #1ebe5a;
      transform: scale(1.05);
    }
    .videos {
      margin: 40px auto;
      max-width: 800px;
      padding: 20px;
    }
    .videos h3 {
      margin-bottom: 20px;
      font-size: 20px;
    }
    .video-wrapper {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .video-wrapper iframe {
      width: 100%;
      height: 220px;
      border-radius: 12px;
      border: none;
    }
    footer {
      margin-top: 40px;
      padding: 20px;
      font-size: 14px;
      background: #f9f9f9;
    }
    /* Floating WhatsApp button */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      animation: pulse 1.5s infinite;
      z-index: 1000;
      text-decoration: none;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }
    @media (max-width: 600px) {
      header { font-size: 22px; }
      .btn { font-size: 1rem; padding: 12px 30px; }
      .video-wrapper iframe { height: 180px; }
    }
  </style>
</head>
<body>

  <!-- Title -->
  <header>WORK FORM HOME</header>

  <!-- Profile Section -->
  <section class="profile">
    <!-- Change this profile photo -->
    <img src="profile.jpg" alt="Profile Photo">
    <h2>!! YOUR NAME HERE !!</h2>
    
    <!-- WhatsApp button (change your number in link) -->
    <a href="https://wa.me/919876543210" target="_blank" class="btn">
      💬 CONTINUE TO CHAT
    </a>
  </section>

  <!-- Testimonial Videos Section -->
  <section class="videos">
    <h3>Team Results & Testimonials</h3>
    <div class="video-wrapper">
      <!-- Replace links with your testimonial videos -->
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
      <iframe src="https://www.youtube.com/embed/ysz5S6PUM-U" allowfullscreen></iframe>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 Work Form Home. All Rights Reserved.
  </footer>

  <!-- Floating WhatsApp Button -->
  <a href="https://wa.me/919876543210" class="whatsapp-float" target="_blank">💬</a>

</body>
</html>
