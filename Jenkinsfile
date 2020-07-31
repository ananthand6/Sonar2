pipeline {
  agent any
 
  tools {nodejs "node"}
 
  stages {
    stage('nodeinstall') {
      steps {
        sh 'npm config ls'
        echo 'Node installation step'
      }
    }
    
    stage('buildangularproject') {
      steps {
        dir ("angular_todo")
        {
        sh 'npm install'
        sh 'npm start'
        }
      }
    }
    
  }
}
