<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>


<!-- PROJECT Header -->
<div align="center">
  <h4>Disclaimer: This guide was typed fast, spellings in guide may differ from actual spellings.</h4>
  <h1 align="center">Git & Github</h1>
  <p align="center">
    A quick demo of Git and Github with deployment to a basic website. 
    <br />
    <br />
    <a href="https://golden-crisp-082db5.netlify.app/">View Demo</a>
    <br />
    <br />
    <br />
  </p>
</div>


<!-- About the project -->
## Getting Started

Here is a quick guide for installing Git on your system, syncing with Github, and using basic Git commands to log file changes locally store and remotely. This guide is demo'd through the build and deployment of a basic website.

<!-- What is Git and Github? -->

## What is difference between Git and Github?

Git is defined as a distributed version control system (VCS) -- in other words, you can track and revert changes as a history log. Github is a web-based service that uses the Git version control system to allow you to store local repos in the cloud so others can collaborate with your codebase.

<!-- Outline -->
## Steps covered in Guide

- [x] Use PowerShell or Ubuntu *(Not covering in this guide)*
  - [x] If using Linux via WSL, install a package manager, I use [Homebrew](https://brew.sh/) *(Not covering in this guide)*
- [ ] Install Git
- [ ] Download a IDE, I'd recommend [VS Code](https://code.visualstudio.com/)
- [ ] Add a local repository *(folder on your system, I typically name my folder 'builds' and keep in my 'documents' folder)*
- [ ] Intialize Git in local repository, Config, Stage, Commit
- [ ] Setup a Github.com Account 
- [ ] Sync you sync with Github.com credentials *(I'm using [Github CLI](https://cli.github.com/) to do this)*
- [ ] Push to Github
- [ ] Deploy your repository to a domain.:)

### Installation

1. You need to install Git on your system
   * [Git](https://git-scm.com/)
        After you install Git, by selecting your operating system. You can make sure Git is installed by running the following command in terminal. If everything installed correctly, Git should return the version that is installed on your computer.
        ```sh
        git --version
        ```
        _Note: you can install Git through PowerShell or via WSL._
2. Install [VS Code](https://code.visualstudio.com/)
3. Create a local folder(repo) (via command line or through File Explorer)
   1. Open folder(repo) in Terminal by dragging into Terminal or open Terminal inside VS Code
4. Initialize folder(repo)
   1. ```sh
        Git init 
        ```
    1. Check to make sure Git was intialized
       1. ```sh
            Git status
            ```
    2. Config your local account
       1. ```sh
            git config --global user.name "Your Name"
            git config --global user.email "your@email.com"
            ```
5. Added a file into your folder(repo)
6. Makes some changes, and save.
7. Stage, Commit, and check Logs
   1. Stage
      1. ```sh
            git add .
            ```
    1. Commit
       1. ```sh
            git commit -m "Commit message"
            ```
    2. Check logs
       1. ```sh
            git log
            ```
8. Setup an Account at [Github](https://github.com/)
9.  Via Termainal (only if Github CLI is installed) enter this prompt
   ```sh
    GH repo GithubUsername/Repository
   ```


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments & Resources

Resources that may be helpful to help kickstart or troubleshoot:

* [Git vs Github](https://www.geeksforgeeks.org/difference-between-git-and-github/#:~:text=Below%20is%20a%20table%20of%20differences%20between%20Git,maintained%20by%20Microsoft.%20%208%20more%20rows%20)
* [Git Cheat Sheet – 50 Git Commands You Should Know](https://www.freecodecamp.org/news/git-cheat-sheet/)
* [ReadME template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

