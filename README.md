## Hi there 👋

<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<div id="badges">
  <a href="your-linkedin-URL">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="your-twitter-URL">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<img src="https://komarev.com/ghpvc/?username=your-github-username&style=flat-square&color=blue" alt=""/>
<h1>
  hey there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>
<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>

Welcome to my GitHub profile! I'm a passionate Full Stack Developer <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> from India, specializing in .NET development. 

- 💻 Currently, I'm working as a Dotnet Developer, utilizing my expertise in C# and .NET to develop robust web applications.
- ✍️ I also enjoy sharing my knowledge through technical blogs, where I write about my experiences, tutorials, and best practices.
- ⚡ In my free time, I love exploring the latest tech articles and staying updated with emerging technologies and best practices.
- 📫 How to reach me: &nbsp; [![Linkedin Badge](https://img.shields.io/badge/-Shekhar-blue?style=flat&logo=Linkedin&logoColor=white)](your-linkedIn-Url)

<div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/dot-net/dot-net-original.svg" title="Dotnet" alt="Dotnet" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/dotnetcore/dotnetcore-original.svg" title=".NET Core" alt=".Net Core" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/jquery/jquery-original-wordmark.svg" title="jQuery" alt="jQuery" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-plain.svg" title="Bootstrap" alt="Bootstrap" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original-wordmark.svg" title="mongoDB"  alt="mongoDB" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/azure/azure-original-wordmark.svg" title="Azure" alt="Azure" width="40" height="40"/>&nbsp;
 <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" title="Postman"  alt="Postman" width="40" height="40"/>&nbsp;
 <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>&nbsp;
</div>

[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=your-GitHub-username&theme=dark&background=000000)](https://git.io/streak-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Your-UserName&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)


name: Latest blog post workflow
on:
  schedule:
    - cron: '30 5,17 * * *'
  workflow_dispatch:

jobs:
  update-readme-with-blog:
    name: Update this repos README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          max_post_count: "4"
          feed_list: "https://medium.com/feed/@shekhartarare"

<!--
**Rutvija09/Rutvija09** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
