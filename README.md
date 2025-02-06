# Java Tap Webinar 1

Starter code: https://github.com/ckechios/tap-java_1-starter

### Install Java

```

sudo apt update
sudo apt install openjdk-21-jdk -y

# check installation
ls -l /usr/lib/jvm/

# based on above java name add lines below
export JAVA_HOME=/usr/lib/jvm/java-21-openjdk-amd64
export PATH=$JAVA_HOME/bin:$PATH

# To persist add above lines to ~/.bashrc in a codespace VM
code ~/.bashrc

```

- Install extension Java
- Ctl + , 
    - disable "inlay hints" 
    - disable "Editor: Code Lens" to get rid of unwanted help
- Intro to jshell
- Hands on Java