pipeline {
  agent {
    docker {
      image 'schoolofdevops/node:4-alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        sh 'npm test'
      }
    }

    stage('package') {
      steps {
        sh 'npm run package'
      }
    }

  }
}