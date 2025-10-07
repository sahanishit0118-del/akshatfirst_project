# akshatfirst_project
this project is based on basics  of network engineering..
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Network Engineering Hub</title>
  <style>
    body{* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body {
  background: #f4f6f8;
  color: #222;
}

header {
  background: #0b3954;
  color: white;
  padding: 1em 2em;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  font-size: 1.5em;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: 500;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  background: linear-gradient(120deg, #0077b6, #00b4d8);
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero button {
  background: white;
  color: #0077b6;
  border: none;
  padding: 10px 20px;
  border-radius: 6px;
  cursor: pointer;
  font-size: 1em;
}

.hero button:hover {
  background: #caf0f8;
}

section {
  padding: 60px 20px;
  max-width: 1000px;
  margin: auto;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
  width: 280px;
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  max-width: 400px;
  margin: 20px auto;
}

input, textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  background: #0077b6;
  color: white;
  border: none;
  padding: 10px;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background: #0096c7;
}

footer {
  background: #0b3954;
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 50px;
}

  </style>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Network Engineering Hub</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#concepts">Concepts</a></li>
        <li><a href="#labs">Labs</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
   <section id="home" class="hero">
    
    <h2>Welcome to Network Engineering Hub</h2>
    <p>Your one-stop resource for mastering networking fundamentals and advanced routing.</p>
    <button onclick="scrollToSection('concepts')">Start Learning</button>
  </section>



  

  <section id="about">
    <h2>About</h2>
    <p>This site is designed for students and professionals looking to strengthen their understanding of computer networks, from OSI models to routing protocols like OSPF, EIGRP, and BGP.</p>
  </section>

  <section id="concepts">
    <h2>Key Concepts</h2>
    <div class="cards">
      <div class="card">
        <h3>OSI Model</h3>
        <p>Understand the 7 layers that define network communication.</p>
      </div>
      <div class="card">
        <h3>Routing Protocols</h3>
        <p>Dive into OSPF, EIGRP, RIP, and BGP with hands-on examples.</p>
      </div>
      <div class="card">
        <h3>Switching</h3>
        <p>Learn how VLANs, STP, and trunking work in Ethernet networks.</p>
      </div>
    </div>
  </section>

  <section id="labs">
    <h2>Labs</h2>
    <p>Practice networking commands and topologies in Packet Tracer or GNS3.</p>
    <ul>
      <li>Configure IP addressing and subnets</li>
      <li>Set up OSPF and EIGRP routing</li>
      <li>Implement VLANs and trunk links</li>
      <li>Test STP, RSTP, and VTP configurations</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Have feedback or collaboration ideas? Reach out!</p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Network Engineering Hub | Built by Deepak Tripathi</p>
  </footer>

  <script src="script.js">function scrollToSection(id) {
  document.getElementById(id).scrollIntoView({ behavior: "smooth" });
}

document.querySelector("form").addEventListener("submit", function (e) {
  e.preventDefault();
  alert("Message sent successfully!");
  this.reset();
});
</script>
</body>
</html>
