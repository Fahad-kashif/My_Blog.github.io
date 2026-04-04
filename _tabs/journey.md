<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f7fa;
      color: #1f2937;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      margin: 80px auto;
      padding: 20px;
      text-align: center;
    }

    #read-journey {
      background-color: #e0f2fe;
      border-radius: 12px;
      padding: 50px 30px;
      box-shadow: 0 8px 15px rgba(0,0,0,0.1);
    }

    #read-journey h2 {
      font-size: 2.5rem;
      color: #0c4a6e;
      margin-bottom: 20px;
    }

    #read-journey p {
      font-size: 1.1rem;
      color: #1e3a8a;
      line-height: 1.6;
      margin-bottom: 30px;
    }

    #read-journey a {
      font-size: 1rem;
      font-weight: 600;
      color: #ffffff;
      background-color: #2563eb;
      padding: 12px 24px;
      border-radius: 9999px;
      text-decoration: none;
      display: inline-block;
    }

    #read-journey a:hover {
      background-color: #1d4ed8;
    }

    /* Responsive */
    @media (max-width: 600px) {
      #read-journey h2 {
        font-size: 2rem;
      }

      #read-journey p {
        font-size: 1rem;
      }

      #read-journey a {
        padding: 10px 20px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <section id="read-journey">
      <h2>🎓 My University Journey</h2>
      <p>
        Discover the projects, events, and experiences that shaped my growth as a Computer Engineering student.
        Every step has been a learning journey worth sharing.
      </p>
      <!-- Your link -->
      - <a href="/posts/my-university-journey/">Read my journey</a>
    </section>
  </div>

</body>
</html>
