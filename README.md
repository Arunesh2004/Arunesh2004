<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Arunesh Sharma - Portfolio</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background-color: #121212;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
    }

    .animal {
      position: absolute;
      width: 100px;
      height: 100px;
      cursor: pointer;
      transition: transform 0.3s ease-in-out;
    }

    .cat {
      background-image: url('https://media.giphy.com/media/26AOMmDgf61rLfKnS/giphy.gif');
      background-size: cover;
      top: 50px;
      left: 100px;
    }

    .dog {
      background-image: url('https://media.giphy.com/media/3o6ZtpxfhwVfBC7dWS/giphy.gif');
      background-size: cover;
      top: 200px;
      left: 300px;
    }

    .animal:hover {
      transform: scale(1.2);
    }

    .animal:active {
      transform: rotate(360deg);
    }

    @keyframes move {
      0% { transform: translateX(0); }
      50% { transform: translateX(100vw); }
      100% { transform: translateX(0); }
    }

    .moving {
      animation: move 5s linear infinite;
    }

    h1, h3, h2, p {
      font-family: 'Fira Code', monospace;
    }

    .badge-link {
      display: inline-block;
      margin: 10px;
    }

    .badge-link img {
      width: 100px;
      height: 40px;
    }

    .animal-info {
      margin-top: 20px;
    }

    .animal-info p {
      font-size: 20px;
    }

  </style>
</head>
<body>

  <h1>👋 Hi, I'm <span style="color:#00BFFF">Arunesh Sharma</span></h1>
  <h3>🌟 A passionate programmer and lifelong learner from India 🌟</h3>

  <hr>

  <h2>🚀 About Me</h2>
  <p>
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=4000&pause=1000&color=00BFFF&center=true&vCenter=true&width=700&lines=🌱+Currently+learning+JAVA%2C+DSA%2C+and+Web+Development;💬+Ask+me+about+C%2C+Java%2C+HTML%2C+CSS%2C+JavaScript;📫+Reach+me+at+sharmaarunesh07%40gmail.com" alt="About Me Typing Animation" />
  </p>

  <hr>

  <h2>🌐 Connect With Me</h2>
  <p>
    <a href="https://www.linkedin.com/in/arunesh-sharma-96b74632a" class="badge-link" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://www.leetcode.com/sharmaarunesh07" class="badge-link" target="_blank">
      <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
    </a>
    <a href="mailto:sharmaarunesh07@gmail.com" class="badge-link" target="_blank">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
  </p>

  <hr>

  <h2>🛠️ Languages and Tools</h2>
  <p>
    <a href="https://www.cprogramming.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="50" height="50" /></a>
    <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS" width="50" height="50" /></a>
    <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML" width="50" height="50" /></a>
    <a href="https://www.java.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="50" height="50" /></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="50" height="50" /></a>
    <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="50" height="50" /></a>
    <a href="https://git-scm.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" width="50" height="50" /></a>
  </p>

  <hr>

  <h2>📊 My GitHub Stats</h2>
  <div>
    <img src="https://github-readme-stats.vercel.app/api?username=arunesh2004&show_icons=true&theme=radical" alt="GitHub Stats" />
    <br />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=arunesh2004&theme=radical" alt="GitHub Streak" />
    <br />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arunesh2004&layout=compact&theme=radical" alt="Top Languages" />
  </div>

  <hr>

  <h2>🏅 GSSOC 24 Badges</h2>
  <details>
    <summary><strong>🎖️ View Badges</strong></summary>
    <p style="display: flex; flex-wrap: wrap; gap: 15px;">
      <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/Postman%20White.png" width="90" height="90" alt="Badge"/>
      <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/1.png" width="90" height="90" alt="Badge"/>
      <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/2.png" width="90" height="90" alt="Badge"/>
    </p>
  </details>

  <hr>

  <h2>🌟 Fun Fact</h2>
  <p>
    <img src="https://readme-jokes.vercel.app/api?hideBorder&theme=radical" alt="Programming Joke" />
  </p>

  <hr>

  <p>✨ <i>Thanks for visiting! Let's connect and code together!</i> ✨</p>

  <div class="animal cat moving" id="cat"></div>
  <div class="animal dog moving" id="dog"></div>

  <script>
    // Event listeners for mouse interactions
    document.getElementById('cat').addEventListener('click', function() {
      alert('You clicked the cat!');
    });

    document.getElementById('dog').addEventListener('click', function() {
      alert('You clicked the dog!');
    });

    document.getElementById('cat').addEventListener('mouseover', function() {
      this.style.filter = 'brightness(1.5)';
    });

    document.getElementById('cat').addEventListener('mouseout', function() {
      this.style.filter = 'brightness(1)';
    });

    document.getElementById('dog').addEventListener('mouseover', function() {
      this.style.filter = 'brightness(1.5)';
    });

    document.getElementById('dog').addEventListener('mouseout', function() {
      this.style.filter = 'brightness(1)';
    });
  </script>

</body>
</html>
