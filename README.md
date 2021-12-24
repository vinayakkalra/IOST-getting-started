# IOST Getting Started

This guide contains the software requirements as well as installation process for getting started with building smart contracts on IOST chain.

- The first thing that we need is a good code editor. The most recommended one is [Visual Studio Code](https://code.visualstudio.com/). Go to this link and install Visual Studio Code.

- The second thing we need is Nodejs installed. You can get the installation guides for your specific operating system [here](https://nodejs.org/en/download/)
- Now the third most important thing that we need is iWallet command line interface that would be used for our smart contracts development. Before we install iWallet CLi, we need to install [Golang](https://go.dev/doc/install) for MacOS, Windows or linux systems that we are on. Run the below command in the terminal to make sure go is successfully installed. If you face issues, please refer to the [GitHub discussions page](https://github.com/mining-devs/IOST-developer-tut-series/discussions)
  > go version 

- Next we need Git LFS(Large File Storage) as a pre-requisite before building IOST. For all windows users, you can skip this step as Git LFS is already included in the [Git For Windows installation](https://git-scm.com/downloads). If you do not have git please go ahead and install it.
  - MacOS Installation
  
  > brew install git-lfs && git lfs install

  - Ubuntu Installation
  
  > sudo apt install -y git-lfs && git lfs install
  
  - CentOS installation
  
  > yum --enablerepo=epel install -y git-lfs && git lfs install
