pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }
    stage('clean mvn') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}