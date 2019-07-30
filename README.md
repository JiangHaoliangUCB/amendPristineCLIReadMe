# Pristine CLI ReadMe

A cli to make it super easy to select a Pristine github template to start from.

## What is Pristine?

[Pristine](https://github.com/etclabscore/pristine) is an open source repository in its original condition.

There are a lack of repositories to start from to build community driven open source projects. Pristine is a complete starting point, it follows a Documentation Driven Development approach, and can be used as a resource to augment existing documentation.



## Before You Get Started (Instructions for Beginners) ##

- If you are a Windows User, you should download, unzip, and open [**Cmder**](<https://cmder.net/>) as your console commander. The advantage of using **Cmder** is its portability and UNIX compatibility. 
- **nvm (node version manager)** is a tool that allows you to download and install Node.js. 
- Download [**nvm for windows**](<https://github.com/coreybutler/nvm-windows/releases>) newest version from GitHub. 
- Unzip the package and follow the installation instructions provided in **nvm-setup.exe**. 
- To check if the installation is successful, run `nvm --version` in **Cmder**. You will see the latest version displayed.
- Once you have finished the installation of **nvm**, you will be able to install [**Node.js**](<https://nodejs.org/en/>). 
- **Node.js** is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. 
- Run `nvm install node` in **Cmder** to install the newest version of **Node.js**. 
- To check the version of **Node.js**, run `node --version` in **Cmder**.
- In order to install the **pristine-cli** module, you also need to have the latest version of [**npm **](<https://www.npmjs.com/get-npm>). 
- The **npm (node package manager)** program is a package manager for **Node.js** packages (or so-called modules). 
- Fortunately, **npm** is distributed with **Node.js**. Once you have successfully installed **Node.js**,  you should be able to use run **npm** in your **Cmder** right away. 
- It should be noted that **npm** is a separate project from **Node.js** and tends to be updated more frequently. It is important to check the version by running `npm --version` in **Cmder**.  

## How to use Pristine CLI

- `npm install -g @etclabscore/pristine-cli`
- to start a new project using the Pristine template, try:`pristine-cli myNewProject`
- follow the prompts to select a template and create a new project to suite your needs


![pristine-cli-test2](https://user-images.githubusercontent.com/364566/60707733-3d8c6a80-9ec1-11e9-9a3e-7943c4e6e9ae.gif)


#### Resources

- [Pristine](https://github.com/etclabscore/pristine)
- [opensource.guide](https://opensource.guide/)
- [Github community profiles for public repositories](https://help.github.com/articles/about-community-profiles-for-public-repositories/)
- [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)
- [pengwynn/flint](https://github.com/pengwynn/flint)
- [Working Backwards](https://www.allthingsdistributed.com/2006/11/working_backwards.html)
- [Literate programming](https://en.wikipedia.org/wiki/Literate_programming)
- [Hammock Driven Development](https://www.youtube.com/watch?v=f84n5oFoZBc)
- [Inversion and The Power of Avoiding Stupidity](https://fs.blog/2013/10/inversion/)
- [choosealicense.com](http://choosealicense.com)

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.
