pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh '''npm i
'''
      }
    }
    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }
    stage('Test') {
      steps {
        sh 'npm test'
        mail(subject: 'chuy se la come', body: 'toda', to: 'jesus.caballero@neoris.com')
      }
    }
  }
}