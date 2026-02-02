# Ex01 Portfolio
## Date: 2/02/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM:

## INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Game Developer Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- CSS Link -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- HERO -->
  <header>
    <div class="hero">
      <h1>Hi, I'm <span>Ram</span></h1>
      <p>Game Developer | Level Designer | Competitive Gamer</p>
      <a href="#games" class="btn">View My Games</a>
    </div>
  </header>

  <!-- ABOUT -->
  <section class="about">
    <h2>About Me</h2>
    <p>
      I'm a passionate game developer focused on immersive gameplay,
      smooth mechanics, and competitive game design.
    </p>
  </section>

  <!-- SKILLS -->
  <section>
    <h2>Game Skills</h2>
    <div class="grid">
      <div class="card">
        <h3>Unity / Unreal</h3>
        <p>Game mechanics & physics</p>
      </div>
      <div class="card">
        <h3>C# / C++</h3>
        <p>Gameplay programming</p>
      </div>
      <div class="card">
        <h3>Level Design</h3>
        <p>Balanced & immersive maps</p>
      </div>
      <div class="card">
        <h3>UI / HUD</h3>
        <p>Clean in-game interfaces</p>
      </div>
    </div>
  </section>

  <!-- GAMES -->
  <section id="games">
    <h2>My Games</h2>
    <div class="grid">
      <div class="card">
        <h3>Battle Royale Arena</h3>
        <p>Fast-paced multiplayer FPS game.</p>
      </div>
      <div class="card">
        <h3>Cyber Runner</h3>
        <p>Neon cyberpunk endless runner.</p>
      </div>
      <div class="card">
        <h3>Zombie Survival</h3>
        <p>Wave-based co-op survival game.</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p> 212224230219 Ram Nithish | Game Portfolio</p>
  </footer>

</body>
</html>

```
## STYLE.CSS
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Orbitron', sans-serif;
}

body {
  background: radial-gradient(circle at top, #0f172a, #020617);
  color: #e5e7eb;
  line-height: 1.6;
}

/* HERO */
header {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 20px;
}

header h1 {
  font-size: 3.2rem;
  text-shadow: 0 0 20px #38bdf8;
}

header span {
  color: #38bdf8;
}

header p {
  margin: 20px auto;
  max-width: 600px;
  color: #9ca3af;
}

.btn {
  display: inline-block;
  padding: 14px 40px;
  border-radius: 40px;
  background: linear-gradient(135deg, #38bdf8, #6366f1);
  color: #020617;
  text-decoration: none;
  font-weight: 700;
  box-shadow: 0 0 25px rgba(56,189,248,0.6);
  transition: transform 0.3s ease;
}

.btn:hover {
  transform: scale(1.08);
}

/* SECTIONS */
section {
  padding: 80px 10%;
}

h2 {
  text-align: center;
  font-size: 2.6rem;
  margin-bottom: 50px;
  color: #38bdf8;
  text-shadow: 0 0 15px rgba(56,189,248,0.6);
}

.about p {
  max-width: 800px;
  margin: auto;
  text-align: center;
  color: #cbd5f5;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
}

.card {
  background: rgba(2,6,23,0.9);
  padding: 30px;
  border-radius: 22px;
  box-shadow: 0 0 40px rgba(0,0,0,0.6);
  transition: transform 0.35s ease, box-shadow 0.35s ease;
}

.card:hover {
  transform: translateY(-12px);
  box-shadow: 0 0 50px rgba(56,189,248,0.6);
}

.card h3 {
  margin-bottom: 15px;
  color: #a5f3fc;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background: #020617;
  color: #9ca3af;
}
```


## OUTPUT:

<img width="1884" height="1032" alt="Screenshot 2026-02-02 090134" src="https://github.com/user-attachments/assets/4c3a0de1-9722-476d-8a2a-b1e9b6dfab45" />

<img width="1880" height="1019" alt="Screenshot 2026-02-02 090154" src="https://github.com/user-attachments/assets/f0023cee-316c-4ed6-9899-6c9874f589c9" />

<img width="1882" height="1027" alt="Screenshot 2026-02-02 090235" src="https://github.com/user-attachments/assets/381409fe-50af-4340-b7eb-75641b619275" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
