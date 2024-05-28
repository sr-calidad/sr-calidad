# Hi there, I'm [Your Name]! 👋

![GitHub Banner](https://raw.githubusercontent.com/srathod19/srathod19/main/github-banner.png)

<p align="center">
  <img src="https://raw.githubusercontent.com/srathod19/srathod19/main/waving-hand.gif" alt="Waving Hand" width="30" height="30" />
  <br>
  <strong>Full Stack Developer | Open Source Enthusiast</strong>
  <br>
  Passionate about coding, technology, and continuous learning.
</p>

## About Me

- 🌱 I’m currently learning **TypeScript, Vite, and React Native**
- 💼 Currently working at **[Your Company]**
- 💬 Ask me about **JavaScript, React, Node.js, and Python**
- 📫 How to reach me: **[Your Email]**
- ⚡ Fun fact: I love 3D modeling and animations.

## 🛠️ Skills

- **Languages:** JavaScript, TypeScript, Python, HTML, CSS
- **Frameworks/Libraries:** React, Node.js, Express, Redux
- **Tools:** Git, Docker, Webpack, Babel
- **Databases:** MongoDB, PostgreSQL, MySQL

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=srathod19&show_icons=true&theme=radical" alt="GitHub Stats" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=srathod19&layout=compact&theme=radical" alt="Top Languages" />
</div>

## 🌐 Connect with Me

- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/yourprofile/)
- Twitter: [Your Twitter Profile](https://twitter.com/yourprofile)
- Portfolio: [Your Portfolio](https://yourportfolio.com)

## 🚀 Projects

### Project 1: [Project Name](https://github.com/srathod19/project-name)

Brief description of the project and its purpose.

- Tech Stack: React, Node.js, Express, MongoDB
- Features: Feature 1, Feature 2, Feature 3

### Project 2: [Project Name](https://github.com/srathod19/project-name)

Brief description of the project and its purpose.

- Tech Stack: TypeScript, Vite, Redux
- Features: Feature 1, Feature 2, Feature 3

## 📊 3D Graphs and Animations

### 3D Graph Example

<div align="center">
  <canvas id="3d-graph" width="600" height="400"></canvas>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r121/three.min.js"></script>
<script>
  var scene = new THREE.Scene();
  var camera = new THREE.PerspectiveCamera(75, 600 / 400, 0.1, 1000);
  var renderer = new THREE.WebGLRenderer();
  renderer.setSize(600, 400);
  document.getElementById('3d-graph').appendChild(renderer.domElement);
  
  var geometry = new THREE.BoxGeometry();
  var material = new THREE.MeshBasicMaterial({ color: 0x00ff00 });
  var cube = new THREE.Mesh(geometry, material);
  scene.add(cube);
  
  camera.position.z = 5;
  
  var animate = function () {
    requestAnimationFrame(animate);
    cube.rotation.x += 0.01;
    cube.rotation.y += 0.01;
    renderer.render(scene, camera);
  };
  
  animate();
</script>

### Animation Example

<div align="center">
  <img src="https://raw.githubusercontent.com/srathod19/srathod19/main/animation.gif" alt="Animation Example" />
</div>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/srathod19/srathod19/main/footer-animation.gif" alt="Footer Animation" width="50" height="50" />
</p>
