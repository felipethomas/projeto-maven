# projeto-maven
Projeto para prática de comandos e utilitários do Apache Maven

### Material de estudo
https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
  
### Configuração do Java no Ubuntu
Comandos  
- sudo gedit /etc/profile  
  
- (inserir ao final do arquivo)  
- export JAVA_HOME=/opt/jdk1.7.0_80  
- export PATH=$JAVA_HOME/bin:$PATH  

Comandos  
- source /etc/profile 
- (reiniciar a sessão do usuário)    
- java -version  
- javac -version  
- echo $JAVA_HOME  
- echo $PATH  
  
### Configuração do Maven no Ubuntu
Comandos  
- sudo gedit /etc/profile  
  
- (inserir ao final do arquivo)   
- export PATH=/home/01308900490/apache-maven-2.2.1/bin:$PATH  
  
Comandos    
- source /etc/profile  
- (reiniciar a sessão do usuário)   
- mvn --version  

### Comandos bash
- PS1="\e[01;32mprojeto-maven:\e[m "
