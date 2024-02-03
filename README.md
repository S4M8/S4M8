  <style>
    body {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    .container {
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }

    .header {
      text-align: center;
      margin-bottom: 20px;
    }

    .card {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      align-items: center;
      margin-bottom: 20px;
      background-color: #fff;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .card img {
      width: 200px;
      border-radius: 20px;
    }

    .technologies, .frameworks, .databases {
      text-align: center;
      margin-top: 20px;
    }

    .row {
      display: flex;
      justify-content: space-around;
      margin-top: 10px;
    }

    .column img {
      width: 50px;
      height: 50px;
      margin: 5px;
    }

    .github-stats {
      text-align: center;
      margin-top: 40px;
    }

    .github-stats img {
      width: 350px;
      height: 200px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="header">
    <h1 class="text">My Tech Stack</h1>
  </div>

  <div class="card">
    <div align="center">
      <img alt="GIF" src="https://i.pinimg.com/originals/9e/a7/2e/9ea72ef078139ced289852e8a4ea0c5c.gif" />
    </div>
  </div>

  <div class="technologies">
    <h2>Languages</h2>
    <div class="row">
      <div class="column">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" />
      </div>
    </div>
  </div>

  <div class="frameworks">
    <h2>Frameworks and Libraries</h2>
    <div class="row">
      <div class="column">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/svelte/svelte-original.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain.svg" />
      </div>
    </div>
  </div>

  <div class="databases">
    <h2>Databases</h2>
    <div class="row">
      <div class="column">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original-wordmark.svg" />
      </div>
    </div>
  </div>

  <div class="github-stats">
    <h2>GitHub Stats</h2>
    <div align="centers">
    <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" />
    </div>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=neon-nomad&hide=html,css,hack&theme=algolia" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=neon-nomad&theme=algolia" />
  </div>
</div>
</body>