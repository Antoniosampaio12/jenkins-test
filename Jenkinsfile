pipeline {
  agent any 
    stages {
      stage('Checkout') {
        steps {
           echo 'Hello Wordl'
         // git 'https://github.com/Antoniosampaio12/jenkins-test.git'
        }
      }
      stage('Build') {
        steps {
          sh 'mkdir -p html'
          sh 'echo "<html><body><h1>Hello,World!</h1></body></html>" > html/index.html'
        }
      }
    }
  }
