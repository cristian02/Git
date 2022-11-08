<a name="readme-top"></a>
<div align="center">
  <h3 align="center">Git commands tutorial </h3>
  <p align="center">
    This tutorial shows how use git commands throught examples.  
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#first-steps">First Steps - Configuration</a>
      <ul>
        <li><a href="#our-first-repo">Let's start - Hands-on</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details
  
<!-- First Steps - Configuration -->
## First Steps 
<h5>Installations</h5>
Installation require that you should execute the following cmd or program

Linux -> apt-get install git 

MAC -> git --version  or download at https://git-scm.com/download/mac 

Win -> https://git-scm.com/download/win 

Other option could be GitHub Desktop: 
https://desktop.github.com/ 

It's important to know the it's better use comand line, GUI tools always has limits.  

<h5>Configuration</h5>
After that, you can set up your git enviroment using git configuration. One of the first things you did was set up your name and email address. (Check out git config information before execute these commands)

git config --global user.name "Cristian Martínez"<br/> 
git config --global user.email crismh2@hotmail.com<br/><br/> 
Other useful commands: <br/> 
git config --global core.editor "code --wait" -> Define VS Code as default editor <br/> 
git config --global -e 

git config --global core.autocrlf true (Windows)<br/> 
git config --global core.autocrlf input (MAC)

<!-- Let's start - Hands-on -->
## Our first repo 
git init -> Start git file <br/> 
git status -> Obtain the repo status <br/> 
git add (element or .) <br/> 
git commit <br/> 
git log -> Allow see commit history <br/> 
git commit --amend -> Allow edit the last commit to include or remove changes <br/> 
git checkout -- (filename) -> Restore the last version in local files 
git reset HEAD (filename) -> Remove file from stage area 
  
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
Cristian Martínez Hernández 

[![LinkedIn][linkedin-shield]][linkedin-url]
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/cristian-mart%C3%ADnez-hern%C3%A1ndez-08043699/
