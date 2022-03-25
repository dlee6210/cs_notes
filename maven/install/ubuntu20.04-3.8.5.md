#1. cd /home/ubuntu2004/programs/

#2. wget https://dlcdn.apache.org/maven/maven-3/3.8.5/binaries/apache-maven-3.8.5-bin.tar.gz

#3. tar -zxvf apache-maven-3.8.5-bin.tar.gz

#4. gedit ~/.bashrc, add:
```
export MAVEN_HOME="/home/ubuntu2004/programs/apache-maven-3.8.5/bin"
export PATH="$PATH:$MAVEN_HOME"
```

#5. mvn -v
