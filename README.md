# Education-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Paramedical Institute Supaul</title>

<style>
*{
  box-sizing:border-box;
  scroll-behavior:smooth;
}
body{
  margin:0;
  font-family:'Segoe UI',sans-serif;
  background:#f4f8fb;
  color:#333;
}

/* HEADER */
header{
  background:linear-gradient(135deg,#0b5ed7,#084298);
  color:#fff;
  padding:35px 20px;
  text-align:center;
}
.logo{
  width:120px;
  margin-bottom:10px;
}

/* NAVBAR */
nav{
  position:sticky;
  top:0;
  background:#084298;
  padding:12px;
  text-align:center;
  z-index:1000;
}
nav a{
  color:white;
  margin:0 15px;
  text-decoration:none;
  font-weight:600;
}
nav a:hover{
  text-decoration:underline;
}

/* HERO IMAGE */
.hero img{
  width:100%;
  max-height:420px;
  object-fit:cover;
}

/* SECTION */
section{
  padding:40px 20px;
  max-width:1100px;
  margin:auto;
}
h2{
  text-align:center;
  color:#0b5ed7;
}

/* CARD */
.card{
  background:white;
  padding:25px;
  margin:25px 0;
  border-radius:10px;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
  transition:0.3s;
}
.card:hover{
  transform:translateY(-5px);
}

/* COURSE GRID */
.course-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:20px;
}

/* FORM */
form input, form textarea{
  width:100%;
  padding:12px;
  margin:10px 0;
  border:1px solid #ccc;
  border-radius:6px;
}
form button{
  background:#0b5ed7;
  color:white;
  padding:12px;
  border:none;
  width:100%;
  font-size:16px;
  border-radius:6px;
  cursor:pointer;
}
form button:hover{
  background:#084298;
}

/* FOOTER */
footer{
  background:#0b5ed7;
  color:white;
  text-align:center;
  padding:18px;
  margin-top:40px;
}

/* MOBILE */
@media(max-width:600px){
  nav a{
    display:block;
    margin:8px 0;
  }
}
</style>
</head>

<body>

<header>
  <img src="logo.png" alt="PMI Logo" class="logo">
  <h1>Paramedical Institute Supaul (PMI)</h1>
  <p>Quality Education in Paramedical Sciences</p>
  <p><strong>Established:</strong> 2021</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#courses">Courses</a>
  <a href="#syllabus">Syllabus</a>
  <a href="#hostel">Hostel</a>
  <a href="#admission">Admission</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  <img src="college.jpg" alt="PMI Building">
</div>

<section id="about">
<h2>About Us</h2>
<div class="card">
<p>
Paramedical Institute Supaul was established in 2021 to provide
high-quality paramedical education with strong practical exposure.
</p>
</div>
</section>

<section id="courses">
<h2>Our Courses</h2>
<div class="course-grid">
  <div class="card">
    <h3>Anaesthesia Technician</h3>
    <p>OT assistance, anesthesia equipment handling, patient monitoring.</p>
  </div>
  <div class="card">
    <h3>Orthopedic & Plaster Technician</h3>
    <p>Plaster application, fracture support, orthopedic care.</p>
  </div>
</div>
</section>

<section id="syllabus">
<h2>Syllabus</h2>
<div class="card">
<ul>
  <li>Anatomy</li>
  <li>Physiology</li>
  <li>Microbiology</li>
  <li>Pharmacology</li>
  <li>Clinical Training</li>
</ul>
</div>
</section>

<section id="hostel">
<h2>Hostel Facility</h2>
<div class="card">
<p>🏨 Hostel available for <strong>Boys & Girls</strong></p>
<p>✔ Secure campus<br>✔ Separate rooms<br>✔ Affordable fees</p>
</div>
</section>

<section id="admission">
<h2>Admission Enquiry</h2>
<div class="card">
<form>
  <input type="text" placeholder="Student Name" required>
  <input type="tel" placeholder="Mobile Number" required>
  <input type="email" placeholder="Email Address">
  <textarea placeholder="Course Interested"></textarea>
  <button type="submit">Submit Enquiry</button>
</form>
</div>
</section>

<section id="contact">
<h2>Contact Us</h2>
<div class="card">
<p><strong>Address:</strong> Supaul, Bihar, India</p>
<p>📞 +91 72090 11525</p>
<p>📞 +91 77173 73420</p>
</div>
</section>

<footer>
<p>© 2026 Paramedical Institute Supaul (PMI)</p>
</footer>

</body>
</html>
