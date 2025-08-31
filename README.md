  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aeronautical Engineering Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://kit.fontawesome.com/2d3d5a8d4a.js" crossorigin="anonymous"></script>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Navbar -->
  <header class="bg-white shadow sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-xl font-bold text-blue-700"><i class="fas fa-plane"></i> Tara</h1>
      <nav class="hidden md:flex space-x-6">
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#education" class="hover:text-blue-600">Education</a>
        <a href="#projects" class="hover:text-blue-600">Projects</a>
        <a href="#skills" class="hover:text-blue-600">Skills</a>
        <a href="#achievements" class="hover:text-blue-600">Achievements</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="max-w-6xl mx-auto px-4 py-16 grid md:grid-cols-2 gap-10 items-center">
    <div>
      <span class="inline-block px-3 py-1 bg-blue-100 text-blue-700 rounded-full text-sm">Aeronautical Engineering</span>
      <h2 class="text-4xl font-bold mt-4">Tara Prasad Panda</h2>
      <p class="text-lg text-gray-600 mt-2">B.Tech in Aeronautical Engineering · India</p>
      <p class="mt-4">Aspiring aeronautical engineer passionate about flight dynamics, propulsion, and lightweight structures. I design, analyze, and prototype aircraft systems with a focus on safety, performance, and manufacturability.</p>
      <div class="mt-6 flex space-x-3">
        <a href="mailto:taraprasadpanda00@gmail.com" class="px-4 py-2 bg-blue-600 text-white rounded-lg"><i class="fas fa-envelope"></i> Email</a>
        <a href="https://github.com/yourhandle" target="_blank" class="px-4 py-2 bg-gray-800 text-white rounded-lg"><i class="fab fa-github"></i> GitHub</a>
        <a href="https://linkedin.com/in/yourhandle" target="_blank" class="px-4 py-2 bg-blue-700 text-white rounded-lg"><i class="fab fa-linkedin"></i> LinkedIn</a>
      </div>
    </div>
    <div>
      <img src="https://images.unsplash.com/photo-1531297484001-80022131f5a1?q=80&w=640&auto=format&fit=crop" alt="Profile" class="rounded-2xl shadow-lg">
    </div>
  </section>

  <!-- About -->
  <section id="about" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold mb-4">About Me</h3>
    <p class="text-gray-600">I am a B.Tech Aeronautical Engineering student, enthusiastic about CFD, CAD/CAE, and UAV design. I aim to contribute to the aviation industry with innovative solutions and practical knowledge.</p>
  </section>

  <!-- Education -->
  <section id="education" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold mb-4">Education</h3>
    <div class="bg-white p-6 rounded-xl shadow">
      <h4 class="font-semibold">B.Tech, Aeronautical Engineering</h4>
      <p class="text-gray-500">Your College / University (2022 – 2026)</p>
      <ul class="list-disc pl-5 text-gray-600 mt-2">
        <li>Core: Aerodynamics, Flight Mechanics, Propulsion, Aircraft Structures, Avionics</li>
        <li>Electives: CFD, Composite Materials, Gas Turbines</li>
        <li>CGPA: 8.8/10 (till 6th sem)</li>
      </ul>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold mb-6">Projects</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="bg-white p-6 rounded-xl shadow">
        <h4 class="font-semibold">Winglet Optimization for Fuel Efficiency</h4>
        <p class="text-gray-600 text-sm mt-1">Reduced induced drag using blended winglet geometry via CFD.</p>
        <ul class="list-disc pl-5 mt-2 text-gray-600">
          <li>CFD meshing & y+ control; achieved ~6.4% drag reduction</li>
          <li>Validated against literature</li>
        </ul>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <h4 class="font-semibold">Micro-UAV Prototype (250mm class)</h4>
        <p class="text-gray-600 text-sm mt-1">Carbon-fiber frame, open-source flight stack, and custom prop selection.</p>
        <ul class="list-disc pl-5 mt-2 text-gray-600">
          <li>Thrust-to-weight ratio 2.3:1; flight time ~14 min</li>
          <li>PID tuning for stable hover</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold mb-6">Skills</h3>
    <div class="grid md:grid-cols-2 gap-6">
      <div class="bg-white p-6 rounded-xl shadow">
        <p>Aerodynamics & CFD (ANSYS/Fluent) – 85%</p>
        <div class="w-full bg-gray-200 h-2 rounded"><div class="bg-blue-600 h-2 rounded" style="width:85%"></div></div>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <p>CAD (SolidWorks/CATIA) – 80%</p>
        <div class="w-full bg-gray-200 h-2 rounded"><div class="bg-blue-600 h-2 rounded" style="width:80%"></div></div>
      </div>
    </div>
  </section>

  <!-- Achievements -->
  <section id="achievements" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold mb-6">Achievements & Certifications</h3>
    <ul class="list-disc pl-5 text-gray-600">
      <li>1st – Aero Design Challenge (Student) 2025</li>
      <li>Top 10 – National CFD Hackathon 2024</li>
      <li>NPTEL – Introduction to Aerodynamics</li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact" class="max-w-6xl mx-auto px-4 py-12">
    <h3 class="text-2xl font-bold mb-4">Contact</h3>
    <p class="text-gray-600">I’m open to internships, research assistant roles, and collaborations in UAVs, CFD, and composite structures.</p>
    <div class="mt-4 space-y-2">
      <p><strong>Email:</strong> taraprasadpanda00@gmail.com</p>
      <p><strong>Phone:</strong> 6370312510</p>
      <p><strong>Instagram:</strong> <a href="https://instagram.com/taraprasadpanda" target="_blank" class="text-blue-600">@taraprasadpanda</a></p>
      <p><strong>Location:</strong> India</p>
    </div>

    <!-- Simple Contact Form -->
    <div class="mt-6 bg-white p-6 rounded-xl shadow">
      <h4 class="font-semibold mb-3">Send me a message</h4>
      <form action="https://formspree.io/f/mwkzjknl" method="POST" class="space-y-4">
        <input type="text" name="name" placeholder="Your Name" class="w-full border rounded px-3 py-2" required>
        <input type="email" name="email" placeholder="Your Email" class="w-full border rounded px-3 py-2" required>
        <textarea name="message" placeholder="Your Message" rows="4" class="w-full border rounded px-3 py-2" required></textarea>
        <button type="submit" class="px-4 py-2 bg-blue-600 text-white rounded-lg">Send</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-100 py-6 mt-10">
    <p class="text-center text-sm text-gray-500">© 2025 Tara Prasad Panda. Built with ❤️ for aeronautics.</p>
  </footer>

</body>
</html>
   
