pipeline{

  agent any

/*  tools{
    maven 'Maven363'
  }
  */

  stages{

    stage('build'){
      steps{
        sh 'npm install'
      }
    }

    stage('test'){
      steps{
        sh 'npm test'
      }
    }

    stage('package'){
      steps{
        sh 'npm run package'
      }
    }

  }

}
