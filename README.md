<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Profile</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f7fc;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
      color: #333;
    }

    .profile-container {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px;
      max-width: 900px;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    h2 {
      font-size: 2rem;
      color: #0077B5;
      margin-bottom: 10px;
    }

    .intro-text {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .icon-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-bottom: 20px;
    }

    .icon-container img {
      transition: transform 0.3s ease, filter 0.3s ease;
    }

    .icon-container img:hover {
      transform: scale(1.1);
      filter: brightness(1.2);
    }

    .social-links {
      display: flex;
      gap: 15px;
      margin-top: 20px;
    }

    .social-links a img {
      transition: transform 0.3s ease;
    }

    .social-links a:hover img {
      transform: scale(1.1);
    }

    .badge {
      border-radius: 50px;
      padding: 5px 20px;
      font-size: 16px;
      background-color: #0077B5;
      color: white;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <div class="profile-container">
    <h2>Hi 👋! My name is Refat and I'm a Web Developer, from Bangladesh</h2>

    <div class="intro-text">
      I'm passionate about creating clean, dynamic, and responsive web applications. Let's connect!
    </div>

    <div class="icon-container">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="40" alt="tailwindcss logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" alt="express logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo" />
    </div>

    <div class="social-links">
      <a href="https://www.linkedin.com/in/mdrefatalhasan/" target="_blank">
        <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&style=for-the-badge" height="35" alt="LinkedIn badge" />
      </a>
      <a href="https://www.x.com/mdrefatalhasan" target="_blank">
        <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&style=for-the-badge" height="35" alt="Twitter badge" />
      </a>
    </div>

    <div class="social-links">
      <a href="mailto:refat.hasan.1314@gmail.com" class="badge">Send Email</a>
    </div>
  </div>

</body>
</html>
