pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker container ls'
        sh 'ls -lha'
      }
    }

    stage('Tests') {
      steps {
        sh 'pwd'
      }
    }

    stage('Aprova��o') {
      steps {
        input 'Aprova?'
        sh 'echo "ok"'
      }
    }

  }
}