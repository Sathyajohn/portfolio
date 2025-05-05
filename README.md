<!DOCTYPE html>
<html lang="en">
<head>
  
  <title>Portfolio</title>
  
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</head>
<body>

  <header>
    <nav>
      <a href="#contact">Contact</a>
      <a href="#education">Education</a>
      <a href="#skills-section">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
    </nav>
    <br>
    <br>
    <h1>Hello  I'm Sathya John</h1>
    <h3>Web Developer | Designer </h3>
      
  </header>

  <section id="about">
    <h2>About Me</h2>
    <img src="c:\Users\Admin\Desktop\man u cris.jfif">
    <p>I’m a passionate developer with skills in HTML, CSS, and JavaScript.</p>
    
  </section>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <section id="projects">
    <h2>Projects</h2>
    <div class="cards-container">
      <div class="card">
        <div class="card-inner">
          <div class="card-front">
            <h3>Project One</h3>
          </div>
          <div class="card-back">
            <p1>This is a cool project about web design.</p>
            <a href="c:\Users\Admin\Desktop\perfume\index.html" target="_blank">PERFUME</a>
          </div>
        </div>
      </div>         
  </section>
  <section id="education">
    <div>
    </div>
  </section>

  <section id="skills-section">
    <h2>My Skills</h2>
    <div class="skills-container">
      <div class="skill">
        <h3>HTML</h3>
        <p>Expert in creating semantic and accessible web pages.</p>
      </div>
      <div class="skill">
        <h3>CSS</h3>
        <p>Proficient in responsive design and modern CSS frameworks.</p>
      </div>
      <div class="skill">
        <h3>JavaScript</h3>
        <p>Experienced in building dynamic and interactive web applications.</p>
      </div>
      <div class="skill">
        <h3>Bootstrap</h3>
        <p>Skilled in using Bootstrap for fast and responsive designs.</p>
      </div>
    </div>
  </section>


  <section class="education-section">
    <h2>Education</h2>
    <div class="education-card">
      <h3>B.Com(Computer Application)</h3>
      <p class="school">Alagappa University</p>
      <p class="date">2021 - 2024</p>
      <p class="description">
        Focused on web development. </p>
    </div>
  </section>
  
  <section id="contact"></section>
  <div class="contact-form">
    <h2>Contact Me</h2>
    <form id="portfolioForm">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required />
  
      <label for="email">Email</label>
      <input type="email" id="email" name="email" required />
  
      <label for="message">Message</label>
      <textarea id="message" name="message" required></textarea>
  
      <button type="submit">Send</button>
      <p id="thankYouMsg" class="hidden">Thanks for reaching out!</p>
    </form>
  

  
    <p>Ph : +91 9360437971</p>
    

    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">

    <p> 
      <a href="mailto:sathyajohna324@gmail.com">
        <i class="fas fa-envelope"></i><p1>sathyajohna324@email.com</p1>
      </a>
    </p>
  </div>
  
  </section>

  
</body>
</html>
<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #3e3857, #928dab);
    color: white;
    scroll-behavior: smooth;
  }
  
  header {
    background: linear-gradient(135deg, #7c63f0, #928dab);
    padding: 20px;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
  }
  
  nav a {
    float: right;
    margin: 0 15px;
    color: #fff;
    text-decoration: none;
    font-size: large;
    font-weight: bold;
    margin-right: 30px;
  }
  #about img{
    float: left;
    margin-left: 250px;
    box-sizing: border-box;
    border-radius: 10px;
  }
  #about p{
    margin-right: 310px;
  }
    
  section {
    padding: 60px 20px;
    text-align: center;
  }
  
  .cards-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
  }
  
  .card {
    width: 250px;
    height: 300px;
    perspective: 1000px;
  }
  
  .card-inner {
    width: 100%;
    height: 100%;
    position: relative;
    transform-style: preserve-3d;
    transition: transform 0.8s;
  }
  
  .card:hover .card-inner {
    transform: rotateY(180deg);
  }
  
  .card-front, .card-back {
    position: absolute;
    width: 100%;
    height: 100%;
    backface-visibility: hidden;
    border: 1px solid #444;
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 10px 10px 10px black;
  }
  
  .card-front {
    background: #333;
    
  }
  
  .card-back {
    background: #555;
    transform: rotateY(180deg);
  }
  .card-back a{
    align-items: center;
    height: 70px;
    padding: 0;
    margin-top: 100px;
    margin-right: 70px;
    margin-left: 70px;
    display: grid;
    box-sizing: border-box;
    background: linear-gradient(135deg, #3e3857, #928dab);
    border-radius: 5px;
    color: white;
    text-decoration: none;
    font-weight: 500;
  }
  .card-back p{
    margin-bottom: 100px;
    margin-left: 60px;
  }
  nav a:hover{
    border: 1px solid black;
    padding: 10px;
    box-shadow: 10px 10px 10px black;
    border-radius: 10px;
    background-color: #5b38f8;
  }
  .contact-form {
  max-width: 400px;
  margin: 0 auto;
  font-family: Arial, sans-serif;
}

.contact-form h2 {
  text-align: center;
}

.contact-form label {
  display: block;
  margin-top: 10px;
}

a i {
  margin-right: 5px;
  color: #007bff;
}
p1{
  text-decoration: none;
  color: white;
  padding: 15px;
  border-radius: 10px;
}
    
a:hover i {
  color: #0056b3;
}


.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
  box-sizing: border-box;
}

.contact-form button {
  margin-top: 15px;
  width: 100%;
  padding: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}

.contact-form button:hover {
  background-color: #0056b3;
}

#thankYouMsg {
  color: rgb(248, 250, 248);
  text-align: center;
  margin-top: 10px;
}

.hidden {
  display: none;
}
.education-section {
  max-width: 800px;
  margin: 50px auto;
  padding: 20px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.education-section h2 {
  text-align: center;
  color: #333;
  margin-bottom: 30px;
}

.education-card {
  margin-bottom: 30px;
  padding: 20px;
  border-left: 5px solid #007acc;
  background: #f9f9f9;
  border-radius: 5px;
}

.education-card h3 {
  margin: 0;
  color: #007acc;
}
.school {
  font-weight: bold;
  color: #555;
}

.date {
  font-style: italic;
  color: #888;
}

.description {
  margin-top: 10px;
  color: #333;
}

#skills-section {
  padding: 60px 20px;
  text-align: center;
  color: white;
}

#skills-section h2 {
  margin-bottom: 30px;
  font-size: 2.5rem;
}

.skills-container {
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
}

.skill {
  background: #5b38f8;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 10px 10px rgba(10, 10, 10, 0.2);
  width: 200px;
  text-align: center;
}

.skill h3 {
  margin-bottom: 10px;
  font-size: 1.5rem;
}

.skill p {
  font-size: 1rem;
  color: #ddd;
}
    
</style>  

<script>
  document.getElementById('portfolioForm').addEventListener('submit', function(e) {
  e.preventDefault(); 

  
  this.reset();

  
  document.getElementById('thankYouMsg').classList.remove('hidden ');
});
</script>
