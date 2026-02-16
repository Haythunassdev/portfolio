<!DOCTYPE html>

<html lang="en">

<head>

&nbsp;   <meta charset="UTF-8">

&nbsp;   <title>HAYTHUNASS | Full-Stack Developer</title>

&nbsp;   <meta name="viewport" content="width=device-width, initial-scale=1.0">



&nbsp;   <style>

&nbsp;       \* { margin:0; padding:0; box-sizing:border-box; font-family:Arial, sans-serif; scroll-behavior:smooth; }

&nbsp;       body { background-color:#0f0f0f; color:#fff; line-height:1.6; }

&nbsp;       header { padding:100px 20px; text-align:center; background:linear-gradient(135deg,#1f1f1f,#111); animation:fadeDown 1.2s ease; }

&nbsp;       header h1 { font-size:48px; letter-spacing:3px; margin-bottom:15px; }

&nbsp;       header p { font-size:18px; color:#aaa; }

&nbsp;       section { padding:80px 10%; opacity:0; transform:translateY(40px); transition:all 0.8s ease; }

&nbsp;       section.show { opacity:1; transform:translateY(0); }

&nbsp;       h2 { margin-bottom:25px; font-size:28px; border-left:4px solid #00adb5; padding-left:10px; }

&nbsp;       .about p { max-width:700px; color:#ccc; }

&nbsp;       .skills ul { list-style:none; display:flex; flex-wrap:wrap; gap:15px; }

&nbsp;       .skills li { background:#1f1f1f; padding:10px 15px; border-radius:6px; border:1px solid #333; transition:0.3s ease; }

&nbsp;       .skills li:hover { background:#00adb5; color:#000; transform:translateY(-3px); }

&nbsp;       .projects { display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:20px; }

&nbsp;       .project-card { background:#1a1a1a; padding:20px; border-radius:8px; border:1px solid #333; transition:0.3s ease; }

&nbsp;       .project-card:hover { transform:translateY(-8px); border-color:#00adb5; box-shadow:0 10px 30px rgba(0,173,181,0.2); }

&nbsp;       .project-card h3 { margin-bottom:10px; }

&nbsp;       .project-card p { color:#bbb; font-size:14px; }

&nbsp;       .contact p { margin-bottom:10px; color:#ccc; }

&nbsp;       a { color:#00adb5; text-decoration:none; }

&nbsp;       a:hover { text-decoration:underline; }

&nbsp;       footer { text-align:center; padding:40px; background:#111; color:#777; font-size:14px; }

&nbsp;       @keyframes fadeDown { from {opacity:0; transform:translateY(-40px);} to {opacity:1; transform:translateY(0);} }

&nbsp;   </style>

</head>

<body>



<header>

&nbsp;   <h1>HAYTHUNASS</h1>

&nbsp;   <p>Full-Stack Developer | Building Scalable Web Applications</p>

</header>



<section class="about">

&nbsp;   <h2>About Me</h2>

&nbsp;   <p>

&nbsp;       I am a passionate Full-Stack Developer specializing in building modern,

&nbsp;       scalable, and secure web applications. I focus on clean architecture,

&nbsp;       performance optimization, and responsive user experiences.

&nbsp;       I enjoy turning complex problems into efficient digital solutions.

&nbsp;   </p>

</section>



<section class="skills">

&nbsp;   <h2>Technical Skills</h2>

&nbsp;   <ul>

&nbsp;       <li>HTML5 \& CSS3</li>

&nbsp;       <li>JavaScript (ES6+)</li>

&nbsp;       <li>React.js</li>

&nbsp;       <li>Node.js</li>

&nbsp;       <li>Express.js</li>

&nbsp;       <li>MongoDB</li>

&nbsp;       <li>REST APIs</li>

&nbsp;       <li>Git \& GitHub</li>

&nbsp;   </ul>

</section>



<section>

&nbsp;   <h2>Projects</h2>

&nbsp;   <div class="projects">

&nbsp;       <div class="project-card">

&nbsp;           <h3>Project Management System</h3>

&nbsp;           <p>

&nbsp;               A full-stack application with authentication, role-based access,

&nbsp;               and task management dashboard built with React and Node.js.

&nbsp;           </p>

&nbsp;       </div>



&nbsp;       <div class="project-card">

&nbsp;           <h3>E-Commerce Platform</h3>

&nbsp;           <p>

&nbsp;               A scalable online store with product management, cart system,

&nbsp;               and secure API integration.

&nbsp;           </p>

&nbsp;       </div>



&nbsp;       <div class="project-card">

&nbsp;           <h3>Business Website</h3>

&nbsp;           <p>

&nbsp;               Responsive business landing page with backend-powered contact form

&nbsp;               and optimized performance.

&nbsp;           </p>

&nbsp;       </div>

&nbsp;   </div>

</section>



<section class="contact">

&nbsp;   <h2>Contact</h2>

&nbsp;   <p>Email: your@email.com</p>

&nbsp;   <p>GitHub: <a href="#">github.com/yourusername</a></p>

&nbsp;   <p>LinkedIn: <a href="#">linkedin.com/in/yourusername</a></p>

</section>



<footer>

&nbsp;   © 2026 HAYTHUNASS. All Rights Reserved.

</footer>



<script>

&nbsp;   const sections = document.querySelectorAll("section");

&nbsp;   const reveal = () => {

&nbsp;       const triggerBottom = window.innerHeight \* 0.85;

&nbsp;       sections.forEach(section => {

&nbsp;           const sectionTop = section.getBoundingClientRect().top;

&nbsp;           if(sectionTop < triggerBottom){ section.classList.add("show"); }

&nbsp;       });

&nbsp;   };

&nbsp;   window.addEventListener("scroll", reveal);

&nbsp;   reveal();

</script>



</body>

</html>



