pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ls'
        sh 'echo "iniciando do build"'
      }
    }

    stage('Tests') {
      steps {
        sh 'pwd'
      }
    }

    stage('Aprova��o') {
      steps {
        input 'Aprova o deploy?'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "fazendo deploy"'
      }
    }

  }
}