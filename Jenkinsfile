pipeline {
  agent any
    
  tools {nodejs "NodeJS"}
    
  stages {
        
   
    stage('Build') {
      steps {
        sh 'npm install regex'
      }
    }  
      
    stage('Test') {
      steps {
        sh 'npm run'
      }
    }
  }
}
