pipeline {

  agent any
 
  stages {
    stage('Build') {
      steps {
            sh 'java -version'
      }
    }

    stage('Test') {
      steps {
          sh "mvn clean install"
      }
    }

    
  }
}
