# Pristine CLI ReadMe

- [What is Pristine?](#heading1)
- [Before Getting Started](#heading2)
- [What is Pristine CLI?](#heading3)
- [How to Use Pristine CLI and Pristine Templates?](#heading4)
- [Resources](#resources)
- [Contributing](#contributing)

<a name = "heading1"></a>
## What is Pristine?  

Previously, there were a lack of repositories to start from to build community driven open source projects. Pristine is a complete starting point, it follows a Documentation Driven Development approach, and can be used as a resource to augment existing documentation. 

[Pristine](https://github.com/etclabscore/pristine) is an open source repository in its original condition that contains conventions and specifications for a project to communicate the problem you are solving, ease onboarding, build and use composable tools, promote open source contribution and engagement, and promote the issue and feature discussion on GitHub itself.

<a name="heading2"></a>

## Before Getting Started ##

#### Cmder 
- If you are a Windows User, you should download, unzip, and open [**Cmder**](<https://cmder.net/>) as your console commander. The advantage of using **Cmder** is its portability and UNIX compatibility. 

#### nvm 
- **nvm (node version manager)** is a tool that allows you to download and install Node.js. 
- Download [**nvm for windows**](<https://github.com/coreybutler/nvm-windows/releases>) newest version from GitHub. 
- Unzip the package and follow the installation instructions provided in **nvm-setup.exe**. 
- To check if the installation is successful, run `nvm --version` in **Cmder**. You will see the latest version displayed.
- Once you have finished the installation of **nvm**, you are ready to install [**Node.js**](<https://nodejs.org/en/>). 

#### Node.js 
- **Node.js** is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. 
- Run `nvm install node` in **Cmder** to install the newest version of **Node.js**. 
- To check the version of **Node.js**, run `node --version` in **Cmder**.

#### npm 
- In order to install the **pristine-cli** module, you also need to have the latest version of [**npm** ](<https://www.npmjs.com/get-npm>) program. 
- The **npm (node package manager)** program is a package manager for **Node.js** packages (or so-called modules). 
- Fortunately, **npm** is distributed with **Node.js**. Once you have successfully installed **Node.js**,  you should be able to use run **npm** in your **Cmder** right away. 
- It should be noted that **npm** is a separate project from **Node.js** and tends to be updated more frequently. It is important to check the version by running `npm --version` in **Cmder**.  

<a name="heading3"></a>

## What is Pristine CLI? ##

**Pristine CLI** is a Commander Line Interface that allows a user to create his or her project based on various pristine DDD templates developed by ETC Lab Core on GitHub. 

Several options of templates to choose from are:

- Pristine Typescript: A template for Typescript-based applications
- Pristine React: A template for React-based applications
- Pristine Typescript Electron: A template for Typescript Electron based applications
- Pristine Typescript React Jade: A WIP template for P2P decentralized applications based on React and Jade’s DApp tooling suite.

<a name="heading4"></a>
## How to use Pristine CLI and Pristine Templates?

- Install the **Pristine CLI** by running `npm install -g @etclabscore/pristine-cli` in **Cmder**.
- To start a new project using the Pristine template, run:`pristine-cli myNewProject`.
- Follow the prompts and use the up and down arrow key to select a template and create a new project to suite your needs. A local repository of your selected Pristine template will be generated in your current directory. You may edit the cloned documents in your favorite Markdown editor. Remember to push the local repository to GitHub once you have finished working on your documentation oriented project. 


![pristine-cli-test2](https://user-images.githubusercontent.com/364566/60707733-3d8c6a80-9ec1-11e9-9a3e-7943c4e6e9ae.gif)

- Another two quicker remote ways to utilize the Pristine templates in your project are to [fork](<https://help.github.com/en/articles/fork-a-repo>) / [clone](<https://help.github.com/en/articles/cloning-a-repository>) the repository 

  ![fork](https://help.github.com/assets/images/help/repository/fork_button.jpg)
  
  ![clone](https://help.github.com/assets/images/help/repository/clone-repo-clone-url-button.png)
  
- Or simply click on the [use this template](<https://help.github.com/en/articles/creating-a-repository-from-a-template>) button of a remote pristine template repository on GitHub @etclabscore. 

  ![use this template](https://help.github.com/assets/images/help/repository/use-this-template-button.png)

- Before you start working on the project offline, remember to pull and merge all the remote changes to your local directory.

<a name="resources"></a>

### Resources

- [Pristine](https://github.com/etclabscore/pristine)
- [Ethereum Classic: Introduction to Pristine — An open standard and template for open-source projects.](<https://medium.com/etclabscore/ethereum-classic-introduction-to-pristine-an-open-standard-and-template-for-open-source-6c0afa757c98>)
- [opensource.guide](https://opensource.guide/)
- [Github community profiles for public repositories](https://help.github.com/articles/about-community-profiles-for-public-repositories/)
- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
- [pengwynn/flint](https://github.com/pengwynn/flint)
- [Working Backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html)
- [Literate programming](https://en.wikipedia.org/wiki/Literate_programming)
- [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc)
- [Inversion and The Power of Avoiding Stupidity](https://fs.blog/2013/10/inversion/)
- [choosealicense.com](http://choosealicense.com)

<a name='contributing'></a>

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.
