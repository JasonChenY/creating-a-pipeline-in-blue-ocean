pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '''-p 3000:3000
-v /sdk/home/echyong/.npm:/root/.npm'''
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}