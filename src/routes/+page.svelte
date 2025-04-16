<script>
  import { fade } from 'svelte/transition';
</script>

<div class="min-h-screen bg-gradient-to-br from-yellow-100 via-blue-100 to-white font-sans text-gray-800 scroll-smooth overflow-x-hidden">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16">

    <!-- Hero Section -->
    <section class="flex flex-col md:flex-row items-center justify-between gap-8 overflow-hidden">
      <div class="text-center md:text-left" in:fade>
        <h1 class="text-4xl sm:text-5xl font-extrabold text-gray-800 mb-4">Francine Chavinda</h1>
        <h2 class="text-xl sm:text-2xl font-bold text-yellow-500 mb-6">Full Stack Systems Developer | Website Developer</h2>
        <div class="flex flex-wrap gap-4 justify-center md:justify-start text-sm text-gray-600">
          <a href="mailto:fechavinda@gmail.com" class="text-lg font-semibold hover:scale-110 transform transition-transform duration-300 text-yellow-500">📧 fechavinda@gmail.com</a>
          <a href="https://www.linkedin.com/in/francine-chavinda-313816299/" class="text-lg font-semibold hover:scale-110 transform transition-transform duration-300 text-blue-600">🔗 LinkedIn</a>
          <a href="https://www.upwork.com/freelancers/~0185cc4e4be17932ef" class="text-lg font-semibold hover:scale-110 transform transition-transform duration-300 text-teal-500">🧑🏽‍💻 Upwork</a>
        </div>
      </div>
      <div class="w-64 h-64 sm:w-80 sm:h-80 rounded-full overflow-hidden shadow-lg flex-shrink-0">
        <img src="images/cinea.jpg" alt="Francine Chavinda" class="object-cover w-full h-full" />
      </div>
    </section>

    <!-- About Me -->
    <section id="about" class="mt-24 text-center md:text-left">
      <h2 class="text-3xl font-bold mb-6 text-yellow-500">About Me</h2>
      <p class="text-lg text-gray-700">
        I’m a passionate System Developer from Malawi with experience in building functional, scalable systems. I specialize in technologies like Golang, JavaScript, TypeScript, Tailwind CSS, and the SvelteKit framework to create seamless and efficient systems. I'm passionate about solving complex challenges with clean, maintainable code. I strive to create software systems that improve everyday life.
      </p>
      <p class="text-lg font-bold text-gray-700 mt-6">
        I’m also open to freelance or remote work where I can help build high-performance applications and solve real-world problems through clean and scalable code.
      </p>
    </section>

    <!-- Skills -->
    <section id="skills" class="mt-24">
      <h2 class="text-3xl font-bold mb-6 text-center text-yellow-500">Skills</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 text-center">
        <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold text-blue-600">Languages</h3>
          <p class="text-lg">Go, JavaScript/TypeScript, SQL</p>
        </div>
        <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold text-teal-500">Frameworks & Libraries</h3>
          <p class="text-lg">SvelteKit, Gorilla Mux, GORM</p>
        </div>
        <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold text-yellow-500">Tools</h3>
          <p class="text-lg">Git, Postman, VS Code, MySQL</p>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="mt-24 px-2">
      <h2 class="text-4xl font-extrabold text-center text-yellow-500 mb-10 tracking-wide">Projects</h2>
      <ul class="space-y-8 max-w-3xl mx-auto">
        <li class="bg-white p-6 border-l-4 border-yellow-400 rounded-lg shadow hover:shadow-md transition">
          <h3 class="text-2xl font-semibold text-teal-700 mb-1">Tilime Honey Estate Produce Website</h3>
          <p class="text-sm text-gray-600 italic mb-2">Tech Stack: SvelteKit (JavaScript & TypeScript), Tailwind CSS</p>
          <ul class="list-disc list-inside text-gray-800 text-lg space-y-1">
            <li>Developed a business website to help boost honey sales through an online presence.</li>
            <li>Focused on responsive UI, customer appeal, and brand storytelling.</li>
          </ul>
          <a href="https://tilimehoney.com" target="_blank" class="text-yellow-600 font-medium hover:underline mt-3 inline-block">🌐 tilimehoney.com</a>
        </li>

        <li class="bg-white p-6 border-l-4 border-yellow-400 rounded-lg shadow hover:shadow-md transition">
          <h3 class="text-2xl font-semibold text-teal-700 mb-1">eNTicket Booking System</h3>
          <p class="text-sm text-gray-600 italic mb-2">Tech Stack: Go, GORM, MySQL, SvelteKit, Tailwind CSS</p>
          <ul class="list-disc list-inside text-gray-800 text-lg space-y-1">
            <li>Collaborated on building an e-ticketing system at All Peoples Innovation Hub.</li>
          </ul>
          <a href="https://eneticket.com" target="_blank" class="text-yellow-600 font-medium hover:underline mt-3 inline-block">🌐 eneticket.com</a>
        </li>

        <li class="bg-white p-6 border-l-4 border-yellow-400 rounded-lg shadow hover:shadow-md transition">
          <h3 class="text-2xl font-semibold text-teal-700 mb-1">Vital Rights Foundation Website</h3>
          <p class="text-sm text-gray-600 italic mb-2">Tech Stack: Wordpress</p>
          <ul class="list-disc list-inside text-gray-800 text-lg space-y-1">
            <li>Developed a website to showcase the organization’s mission and increase awareness of sexual reproductive health rights.</li>
          </ul>
          <a href="https://vitalrightsfoundation.com" target="_blank" class="text-yellow-600 font-medium hover:underline mt-3 inline-block">🌐 vitalrightsfoundation.com</a>
        </li>
      </ul>
    </section>

    <!-- Experience -->
    <section id="experience" class="mt-24 max-w-3xl mx-auto px-4">
      <h2 class="text-3xl font-bold mb-10 text-center text-yellow-500">Experience</h2>
      <div class="space-y-8">
        <div class="bg-white p-8 rounded-2xl shadow-lg border border-gray-100 transition-transform hover:scale-105 duration-300">
          <h3 class="text-xl font-semibold text-teal-600">Systems Developer Intern</h3>
          <p class="text-sm text-gray-500 mb-2">All People's Innovation Hub</p>
          <p class="text-base text-gray-700 mt-4">
            Supported frontend and backend development using Go and SvelteKit. Integrated databases with GORM and conducted feature testing to enhance system performance and user experience.
          </p>
        </div>
      </div>
    </section>

    <!-- Education -->
    <section id="education" class="mt-24 max-w-3xl mx-auto px-4">
      <h2 class="text-3xl font-bold mb-10 text-center text-yellow-500">Education</h2>
      <div class="space-y-8">
        <div class="bg-white p-8 rounded-2xl shadow-lg border border-gray-100 transition-transform hover:scale-105 duration-300">
          <h3 class="text-xl font-semibold text-teal-600">Bachelor’s Degree in Computer Systems & Security</h3>
          <p class="text-base text-gray-700 mt-4">
            Malawi University of Science and Technology (MUST)
          </p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="mt-24 mb-16 text-center px-4">
      <h2 class="text-4xl font-extrabold mb-6 text-yellow-500 tracking-wide">Get in Touch</h2>
      <div class="space-y-4 text-base text-gray-800">
        <p>📧 <span class="font-medium text-xl text-gray-900">Email:</span> <a href="mailto:fechavinda@gmail.com" class="text-yellow-600 font-semibold text-xl hover:underline">fechavinda@gmail.com</a></p>
        <p>🔗 <span class="font-medium text-xl text-gray-900">LinkedIn:</span> <a href="https://www.linkedin.com/in/francine-chavinda-313816299/" target="_blank" class="text-yellow-600 font-semibold text-xl hover:underline">linkedin.com/in/francine-chavinda</a></p>
        <p>🧑🏽‍💻 <span class="font-medium text-xl text-gray-900">Upwork:</span> <a href="https://www.upwork.com/freelancers/~0185cc4e4be17932ef" target="_blank" class="text-yellow-600 font-semibold text-xl hover:underline">upwork.com/freelancers/~0185cc4e4be17932ef</a></p>
      </div>
    </section>
  </div>
</div>

<style>
  :global(html) {
    scroll-behavior: smooth;
  }

  :global(body) {
    margin: 0;
    font-family: 'Inter', sans-serif;
    overflow-x: hidden;
  }
</style>
