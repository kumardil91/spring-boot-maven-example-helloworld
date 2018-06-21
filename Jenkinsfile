node { 
   stage('SCM Checkout') {
    git 'https://github.com/kumardil91/spring-boot-maven-example-helloworld'
   }
   stage('Build'){
   sh 'mvn package'
   }
 }
