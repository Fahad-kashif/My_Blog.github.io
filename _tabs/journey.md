
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* ------------------- */
    /* Global Styles */
    /* ------------------- */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f7fa;
      color: #1f2937;
    }

    a {
      text-decoration: none;
    }

    /* ------------------- */
    /* Container */
    /* ------------------- */
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 40px 20px;
    }

    /* ------------------- */
    /* Section Title */
    /* ------------------- */
    h1, h2, h3 {
      margin: 0;
      padding: 0;
    }

    /* ------------------- */
    /* Read My Journey Section */
    /* ------------------- */
    #read-journey {
      background: linear-gradient(90deg, #ebf8ff 0%, #dbeafe 100%);
      border-radius: 16px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.08);
      padding: 60px 40px;
      text-align: center;
      margin: 80px 0;
    }

    #read-journey h2 {
      font-size: 2.75rem;
      color: #1e3a8a;
      font-weight: 800;
      margin-bottom: 20px;
    }

    #read-journey p {
      font-size: 1.2rem;
      color: #334155;
      line-height: 1.8;
      max-width: 700px;
      margin: 0 auto 30px auto;
    }

    #read-journey .link-card {
      background: #ffffff;
      padding: 30px;
      border-radius: 10px;
      border: 1px solid #e2e8f0;
      display: inline-block;
      text-align: center;
    }

    #read-journey .link-card h3 {
      font-size: 1.8rem;
      color: #1e293b;
      margin-bottom: 15px;
    }

    #read-journey .link-card p {
      font-size: 1rem;
      color: #64748b;
      line-height: 1.6;
      margin-bottom: 20px;
    }

    #read-journey .link-card a {
      display: inline-block;
      font-size: 1.05rem;
      font-weight: 600;
      color: #2563eb;
      padding: 12px 24px;
      border-radius: 9999px;
      border: 1px solid #2563eb;
      transition: all 0.3s ease;
    }

    #read-journey .link-card a:hover {
      background-color: #2563eb;
      color: #ffffff;
      box-shadow: 0 5px 15px rgba(37,99,235,0.3);
    }

    /* ------------------- */
    /* Responsive */
    /* ------------------- */
    @media (max-width: 768px) {
      #read-journey {
        padding: 40px 20px;
      }

      #read-journey h2 {
        font-size: 2.2rem;
      }

      #read-journey p {
        font-size: 1rem;
      }

      #read-journey .link-card h3 {
        font-size: 1.5rem;
      }

      #read-journey .link-card p {
        font-size: 0.95rem;
      }

      #read-journey .link-card a {
        font-size: 0.95rem;
        padding: 10px 20px;
      }
    }
  </style>
</head>
<body>

  <div class="container">

    <!-- ========================= -->
    <!-- Read My Journey Section -->
    <!-- ========================= -->
    <section id="read-journey">
      <h2>🎓 My University Journey</h2>
      <p>
        Explore the milestones, projects, and experiences that shaped my growth as a Computer Engineering student.
        From coding challenges to leadership events, every step is a story worth reading.
      </p>

      <div class="link-card">
        <h3>Discover My Story</h3>
        <p>
          Learn how university shaped my technical and leadership skills through real projects, events, and personal growth.
        </p>
        <!-- Using your exact Markdown-style link -->
        <div>
          - <a href="/posts/my-university-journey/">Read my journey</a>
        </div>
      </div>
    </section>

  </div>

</body>
</html>
