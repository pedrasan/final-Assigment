<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="Tennis for All - Learn, Play, Compete."/>
  <title>Tennis for All</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
      background-color: #f8f8f8;
      color: #333;
    }

    header {
      background-color: #00529B;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav ul {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      list-style: none;
      padding: 0;
      background-color: #003d73;
      margin: 0;
    }

    nav ul li {
      margin: 10px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      border-bottom: 3px solid #ccc;
      padding-bottom: 10px;
      color: #00529B;
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 20px 0;
    }

    figcaption {
      font-size: 0.9em;
      color: #555;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    table, th, td {
      border: 1px solid #999;
    }

    th, td {
      padding: 10px;
      text-align: left;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 500px;
    }

    label {
      font-weight: bold;
    }

    input, textarea {
      padding: 8px;
      font-size: 1em;
    }

    input[type="submit"] {
      background-color: #00529B;
      color: white;
      border: none;
      cursor: pointer;
      padding: 10px;
    }

    input[type="submit"]:hover {
      background-color: #003d73;
    }

    footer {
      background-color: #00529B;
      color: white;
      text-align: center;
      padding: 15px;
    }

    .nested-list ul {
      margin-left: 20px;
    }

    iframe {
      width: 100%;
      height: 360px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Tennis for All</h1>
</header>

<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About Tennis</a></li>
    <li><a href="#learn">Learn</a></li>
    <li><a href="#events">Events</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#join">Join Us</a></li>
  </ul>
</nav>

<!-- HOME -->
<section id="home">
  <h2>Welcome to Tennis for All</h2>
  <p>Explore everything from tennis history and tips to tournaments and local events.</p>
  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f1/Tennis_for_two_gameplay.jpg/800px-Tennis_for_two_gameplay.jpg" alt="Vintage tennis video game">
    <figcaption>Even early video games like “Tennis for Two” celebrated the sport.</figcaption>
  </figure>
</section>

<!-- ABOUT -->
<section id="about">
  <h2>About Tennis</h2>
  <p>Tennis began in the late 1800s and has grown into one of the most popular sports in the world. Played by professionals and amateurs alike, it’s both competitive and fun.</p>
  <ul>
    <li>Top 5 Tennis Players:
      <ol>
        <li>Roger Federer</li>
        <li>Serena Williams</li>
        <li>Rafael Nadal</li>
        <li>Novak Djokovic</li>
        <li>Steffi Graf</li>
      </ol>
    </li>
  </ul>
  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Rafael_Nadal_%282015%29.jpg/800px-Rafael_Nadal_%282015%29.jpg" alt="Rafael Nadal playing tennis">
    <figcaption>Rafael Nadal, known for his dominance on clay courts.</figcaption>
  </figure>
</section>

<!-- LEARN -->
<section id="learn">
  <h2>Learn to Play</h2>
  <p>Here are the basics of getting started with tennis:</p>
  <div class="nested-list">
    <ul>
      <li>Serving
        <ul>
          <li>Overhand Serve</li>
          <li>Underhand Serve</li>
        </ul>
      </li>
      <li>Scoring
        <ul>
          <li>15, 30, 40, game</li>
          <li>Tiebreak Rules</li>
        </ul>
      </li>
    </ul>
  </div>

  <iframe 
    src="https://www.youtube.com/embed/sN7wF2rYY2c" 
    title="Tennis Serving Tutorial" 
    allowfullscreen 
    aria-label="Beginner tennis serve tutorial with subtitles">
  </iframe>
  <figcaption>Video: How to Serve in Tennis (YouTube)</figcaption>
</section>

<!-- EVENTS -->
<section id="events">
  <h2>Upcoming Tennis Events</h2>
  <table>
    <thead>
      <tr>
        <th>Event</th>
        <th>Location</th>
        <th>Date</th>
        <th>Level</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Wimbledon</td>
        <td>London</td>
        <td>July 2025</td>
        <td>Professional</td>
      </tr>
      <tr>
        <td>Local Club Match</td>
        <td>Bogotá</td>
        <td>August 3</td>
        <td>Amateur</td>
      </tr>
    </tbody>
  </table>
  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/2019_Wimbledon_Men%27s_Singles_Final_-_Federer_vs._Djokovic_18.jpg/800px-2019_Wimbledon_Men%27s_Singles_Final_-_Federer_vs._Djokovic_18.jpg" alt="Wimbledon Final match">
    <figcaption>Federer and Djokovic in a historic Wimbledon final.</figcaption>
  </figure>
</section>

<!-- GALLERY -->
<section id="gallery">
  <h2>Photo Gallery</h2>
  <div class="gallery-grid">
    <figure>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Junior_tennis_match.jpg/800px-Junior_tennis_match.jpg" alt="Junior tennis match">
      <figcaption>Youth tennis match at a local tournament.</figcaption>
    </figure>
    <figure>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Tennis_Racket_Closeup.jpg/800px-Tennis_Racket_Closeup.jpg" alt="Close-up of tennis racket">
      <figcaption>Essential gear: A good racket makes all the difference.</figcaption>
    </figure>
  </div>
</section>

<!-- JOIN US -->
<section id="join">
  <h2>Join Our Community</h2>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Message:</label>
    <textarea id="message" rows="4" name="message"></textarea>

    <input type="submit" value="Send">
  </form>

  <figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/26/Tennis_Players_Shaking_Hands.jpg/800px-Tennis_Players_Shaking_Hands.jpg" alt="Players shaking hands">
    <figcaption>Join us and become part of the tennis family!</figcaption>
  </figure>
</section>

<footer>
  <p>&copy; 2025 Tennis for All | Created by Santiago Pedraza</p>
</footer>

</body>
</html>
