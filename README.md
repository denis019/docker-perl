## Docker for Perl development
**Use only for development env!**
 ### Features
 - Remote debugging enabled for IntelliJ IDEA and other JetBrains IDE
 ### Installation
 1. Clone the repository in your project
    ```
    git clone git@github.com:denis019/docker-perl.git
    ```
 2. Run docker
     ```
     cd docker-perl
     docker-compose up --build -d
     ```
 ### PhpStorm setup
 1. Install the following plugins
  - https://plugins.jetbrains.com/plugin/7796-perl/
  - https://plugins.jetbrains.com/plugin/11328-perl-docker-support/
 2. Setup perl interpreter
  - go to Language & Framework > Perl5 > Project and select the perl bin executable from running docker container