# AWS_prototyping

****************** Java Install ************************

From https://tecadmin.net/install-oracle-java-8-ubuntu-via-ppa/

    $ sudo add-apt-repository ppa:webupd8team/java
    $ sudo apt-get update
    $ sudo apt-get install oracle-java8-installer
    
  Configuring Java Environment
    
    $ sudo apt-get install oracle-java8-set-default
  
  Now edit /etc/environment configuration file and add following entries to set JAVA_HOME and JRE_HOME environment variables.
  
    JAVA_HOME=/usr/lib/jvm/java-8-oracle
    JRE_HOME=/usr/lib/jvm/java-8-oracle/jre

******************* Git Install ****************************

From git-scm.com

    Download for Linux and Unix Debian/Ubuntu
        $ sudo apt-get install git
        $ git --version

        $ git config --global user.name "YOUR NAME"
        $ git config --global user.email "YOUR EMAIL ADDRESS"

From https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#platform-linux

From https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/

        sudo apt-get install geomview    
        clip < ~/.ssh/id_rsa.pub
        
******************* NGINX Install ****************************

from https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-14-04-lts

******************* Jenkins Install ****************************


******************* Chef Install *******************************
from https://learn.chef.io/tutorials/learn-the-basics/ubuntu/aws/set-up-a-machine-to-manage/#step1

****************** Emacs Install and Tutorial ******************
from http://www.jesshamrick.com/2012/09/10/absolute-beginners-guide-to-emacs/
****************** Maven Install *******************************
https://www.mkyong.com/maven/how-to-install-maven-in-ubuntu/




