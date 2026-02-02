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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Modern Portfolio | Ram</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background: #0f172a; color: #e5e7eb; }

    header {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
    }

    header h1 { font-size: 3rem; }
    header span { color: #38bdf8; }
    header p { margin: 20px 0; color: #9ca3af; }

    .btn {
      display: inline-block;
      padding: 12px 30px;
      border-radius: 30px;
      background: linear-gradient(135deg, #38bdf8, #6366f1);
      color: #000;
      text-decoration: none;
      font-weight: 600;
    }

    section { padding: 80px 10%; }

    h2 {
      text-align: center;
      font-size: 2.5rem;
      margin-bottom: 50px;
    }

    .about p {
      max-width: 800px;
      margin: auto;
      text-align: center;
      color: #cbd5f5;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .card {
      background: #020617;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.4);
      transition: transform 0.3s ease;
    }

    .card:hover { transform: translateY(-10px); }

    .card h3 { margin-bottom: 15px; color: #38bdf8; }

    footer {
      text-align: center;
      padding: 30px;
      background: #020617;
      color: #9ca3af;
    }
  </style>
</head>
<body>

  <header>
    <div>
      <h1>Hi, I'm <span>RAM</span></h1>
      <p>Modern Web Developer | UI/UX Lover | Tech Explorer</p>
      <a href="#projects" class="btn">View My Work</a>
    </div>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>
      I'm a passionate web developer who loves building modern, fast and user-friendly websites.
      I focus on clean UI, smooth animations and responsive design.
    </p>
  </section>

  <section>
    <h2>Skills</h2>
    <div class="skills">
      <div class="card"><h3>HTML5</h3><p>Semantic and accessible markup</p></div>
      <div class="card"><h3>CSS3</h3><p>Modern layouts & animations</p></div>
      <div class="card"><h3>JavaScript</h3><p>Interactive & dynamic UI</p></div>
      <div class="card"><h3>React</h3><p>Component-based development</p></div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Social Media App</h3>
        <p>Cross-platform app with chat & notifications.</p>
      </div>
      <div class="card">
        <h3>Birthday Website</h3>
        <p>Aesthetic interactive birthday surprise site.</p>
      </div>
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>Modern personal portfolio design.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>RRR 2026 Ram Nithish. All rights reserved.</p>
  </footer>

</body>
</html>
```


## OUTPUT:

<img width="1893" height="1038" alt="Screenshot 2026-02-02 085309" src="https://github.com/user-attachments/assets/28f6c8e7-dc4d-4feb-88be-9d5116ab9a9d" />


<img width="1885" height="1038" alt="Screenshot 2026-02-02 085410" src="https://github.com/user-attachments/assets/a51a5769-12cc-4ca6-bd3f-4dcd0f694df9" />


<img width="1885" height="1036" alt="Screenshot 2026-02-02 085451" src="https://github.com/user-attachments/assets/c9b17505-4066-48f5-b88a-3988586c7673" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
