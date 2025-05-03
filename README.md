/beach-site
├── index.html           ← Home
├── shops.html
├── eats.html
├── things-to-do.html
├── water-fun.html
├── style.css            ← Shared beachy styles
└── images/              ← Optional: photos of the beach, rental, etc.

body {
  font-family: 'Segoe UI', sans-serif;
  background: #e0f7fa;
  color: #004d40;
  margin: 0;
  padding: 0;
}

header {
  background: #00acc1;
  color: white;
  padding: 20px;
  text-align: center;
  background-image: url('images/beach-banner.jpg'); /* optional */
  background-size: cover;
  background-position: center;
}

nav {
  background: #00838f;
  text-align: center;
  padding: 10px 0;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 20px;
  max-width: 900px;
  margin: auto;
}

footer {
  background: #004d40;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome to Our Beach Rental</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Beachside Bliss Rental</h1>
  <p>Relax. Explore. Enjoy your stay!</p>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="shops.html">Shops</a>
  <a href="eats.html">Places to Eat</a>
  <a href="things-to-do.html">Things to Do</a>
  <a href="water-fun.html">Water Fun</a>
</nav>

<section>
  <h2>Welcome to Your Home Away From Home!</h2>
  <p>Our cozy beachfront rental is your perfect escape. Enjoy the ocean view, walk to shops and restaurants, and explore all the coastal town has to offer.</p>
</section>

<footer>
  <p>Contact us anytime at [Phone Number] | [Email]</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Local Shops</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Local Shops</h1>
</header>

<nav>
  <a href="index.html">Home</a>
  <a href="shops.html">Shops</a>
  <a href="eats.html">Places to Eat</a>
  <a href="things-to-do.html">Things to Do</a>
  <a href="water-fun.html">Water Fun</a>
</nav>

<section>
  <h2>Shop Like a Local</h2>
  <ul>
    <li><strong>Sandy Shores Boutique</strong> – Beachwear & souvenirs</li>
    <li><strong>Coastal Market</strong> – Fresh produce & local snacks</li>
    <li><strong>Boardwalk Books</strong> – Local reads & gifts</li>
  </ul>
</section>

<footer>
  <p>Happy shopping!</p>
</footer>

</body>
</html>
