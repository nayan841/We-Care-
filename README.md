<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>We Care - Empowering Dentists</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #004d40;
      color: #fff;
      text-align: center;
      padding: 2rem;
    }
    header img {
      height: 80px;
    }
    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      color: #004d40;
    }
    ul {
      list-style: disc;
      margin-left: 1.5rem;
    }
    .poll {
      margin-top: 2rem;
      background: #e0f2f1;
      padding: 1rem;
      border-radius: 8px;
    }
    .poll input[type="radio"] {
      margin-right: 0.5rem;
    }
    .comment-section {
      display: none;
      margin-top: 1rem;
    }
    .footer {
      text-align: center;
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #555;
    }
  </style>
</head>
<body>
  <header>
    <h1>WE CARE</h1>
    <p>Empowering Dentists. Guiding Patients.</p>
  </header>
  <section>
    <h2>The Problem</h2>
    <p>In India, many skilled dentists struggle with visibility. Meanwhile, patients find it difficult to identify qualified and trusted professionals, often relying on unverified online sources or word-of-mouth.</p>

    <h2>Our Solution</h2>
    <p>We Care is building a platform where verified dentists can showcase their experience, ratings, location, and the number of successful treatments. This allows patients to find the right dentist with confidence and transparency.</p>

    <h2>Key Features</h2>
    <ul>
      <li>Verified Dentist Profiles with ID and Degree Checks</li>
      <li>Ratings and Reviews from Real Patients</li>
      <li>Location-Based Discovery</li>
      <li>Success-Based Commission (only 10%)</li>
      <li>Mobile-Friendly and Easy to Use</li>
    </ul>

    <h2>Why Join Early?</h2>
    <p>If you're a dentist, your early feedback will shape this platform. We aim to solve your visibility issues and grow your reach—starting with 100 committed dentists.</p>

    <div class="poll">
      <p>Do you think this is a good idea?</p>
      <label><input type="radio" name="feedback" value="good" onclick="toggleComment(false)" /> Good Idea</label><br/>
      <label><input type="radio" name="feedback" value="improve" onclick="toggleComment(true)" /> Needs Improvement</label>

      <div class="comment-section" id="commentSection">
        <label for="comments">Please share your suggestions:</label><br/>
        <textarea id="comments" rows="4" cols="50" placeholder="Type here..."></textarea>
      </div>
    </div>

    <p style="margin-top: 2rem; font-weight: bold;">Share this with fellow dentists. Our first milestone: 100 Dentists who believe in We Care.</p>
  </section>

  <div class="footer">
    <p>&copy; 2025 We Care. All rights reserved.</p>
  </div>

  <script>
    function toggleComment(show) {
      document.getElementById('commentSection').style.display = show ? 'block' : 'none';
    }
  </script>
</body>
</html>
