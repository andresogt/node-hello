pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
//    stage('Git') {
//      steps {
//        git 'https://github.com/andresogt/node-hello.git'
//      }
//    }
     
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }        
    
  }
}



   