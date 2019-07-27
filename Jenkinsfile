pipeline {
  agent {
    label 'jenkins-slave'
  }
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/brentlaster/gradle-greetings.git'
      }
    }
    stage('Compile') {
      steps {
        sh 'echo gradle build will go here'
      }
    }
  }
}