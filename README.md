<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&display=swap');

    .header {
        display: flex;
        flex-flow: column nowrap;
        font-family: 'Roboto Mono';
        background-color: #0D1117;
        color: white;
        margin-bottom: 1em;
        padding: 1em 0;
    }

    .header .intro {
        padding: 4em 0;
    }

    .header .introtext {
        font-size: 3em;
        width: 80%;
        margin: auto;
        max-width: 580px;
        padding: 10px 20px;
        border-radius: 3px;
        line-height: .5;
    }

    .header .name {
        font-size: 5em;
        font-weight: 600;
        width: 80%;
        margin: auto;
        max-width: 580px;
        padding: 10px 20px;
        margin-top: 0px;
        line-height: 1;
    }

    .header .social {
        display: flex;
        justify-content: center;
    }

    .header .social > a {
        margin: 0 1em;
    }

    .content {
        display: flex;
        flex-flow: column nowrap;
        justify-content: space-between;
    }

    .content .skills {
        display: flex;
        justify-content: space-evenly;
        align-content: center;
        background-color: #0D1117;
        padding: .5em 1em;
        margin-bottom: 1em;
    }

    .social > a,
    .skills a {
        display: flex;
    }

    .content .stats {
        display: flex;
        gap: 1em;
        margin-bottom: 1em;
        justify-content: center;
    }

    .content .contribution,
    .content .stats > * {
        background-color: #0D1117;
    }
</style>

<div class="header">
    <div class="intro">
        <div class="introtext">Hi 👋🏼, I'm</div>
        <div class="name">Gui</div>
    </div>
    <div class="social">   
        <a href="mailto:gbrunow@outlook.com" target="_blank"><img src="https://img.shields.io/badge/-Email-0D1117?style=for-the-badge&logo=gmail&logoColor=00B9EC"></a>
        <a href="https://www.linkedin.com/in/gbrunow" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00B9EC"></a> 
        <a href="https://www.instagram.com/gbrunow" target="_blank"><img src="https://img.shields.io/badge/-Instagram-0D1117?style=for-the-badge&logo=instagram&logoColor=00B9EC"></a>
    </div>
</div>

<div class="content">
    <div class="skills">
        <a href="#"><img src="https://img.shields.io/badge/-TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-HTML5-0D1117?style=flat-square&logo=html5&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-CSS3-0D1117?style=flat-square&logo=css3&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-SAAS-0D1117?style=flat-square&logo=sass&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-Node-0D1117?style=flat-square&logo=javascript&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-Angular-0D1117?style=flat-square&logo=angular&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-React-0D1117?style=flat-square&logo=react&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-GitHub-0D1117?style=flat-square&logo=github&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/-Git-0D1117?style=flat-square&logo=git&logoColor=00B9EC"></a>
        <a href="#"><img src="https://img.shields.io/badge/Markdown-%230D1117.svg?style=flat-square&logo=markdown&logoColor=00B9EC"></a>
    </div>
    <div class="stats">
        <img alt="Gui's Github Stats" src="https://github-readme-stats.vercel.app/api?username=gbrunow&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=0D1117&title_color=00B9EC&icon_color=00B9EC"/>
        <img alt="Gui's Github Stats" src="https://github-readme-streak-stats.herokuapp.com/?user=gbrunow&theme=highcontrast&hide_border=true&background=0D1117&ring=00B9EC&fire=00B9EC&currStreakLabel=00B9EC"/>
    </div>
    <div class="contribuition">
        <a href="#"><img alt="Gui's Activity Graph" src="https://activity-graph.herokuapp.com/graph?username=gbrunow&custom_title=Gui's%20Contribution%20Graph&bg_color=0D1117&color=00B9EC&line=FFFFFF&point=00B9EC&hide_border=true" /></a>
    </div>
</div>
