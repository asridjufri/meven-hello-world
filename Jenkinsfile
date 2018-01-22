pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'mvn clean install'
          }
        }
        stage('ssh copy') {
          steps {
            sh 'mvn clean'
          }
        }
      }
    }
  }
}