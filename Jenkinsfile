pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'mvn install'
      }
    }
    stage('test') {
      steps {
        sh 'mvn test'
      }
    }
  }
}