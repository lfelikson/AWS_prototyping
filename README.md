# AWS_prototyping
From https://tecadmin.net/install-oracle-java-8-ubuntu-via-ppa/

    $ sudo add-apt-repository ppa:webupd8team/java
    $ sudo apt-get update
    $ sudo apt-get install oracle-java8-installer
    
  Configuring Java Environment
    
    $ sudo apt-get install oracle-java8-set-default
  
  Now edit /etc/environment configuration file and add following entries to set JAVA_HOME and JRE_HOME environment variables.
  
    JAVA_HOME=/usr/lib/jvm/java-8-oracle
    JRE_HOME=/usr/lib/jvm/java-8-oracle/jre

