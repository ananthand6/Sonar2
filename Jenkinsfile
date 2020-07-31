pipeline {
  agent any
 
  tools {nodejs "node"}
 
  stages {
    stage('Example') {
      steps {
        sh 'npm config ls'
        sh 'dir angular'
        sh 'npm install'
        sh 'npm start'
        echo 'Hiii'
      }
    }
  }
}
