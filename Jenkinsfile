pipeline {
  agent any
  stages {
    stage('Check out ') {
      steps {
        git(url: 'https://github.com/rhouma-jeder/curriculum-app-rje', branch: 'master')
      }
    }

    stage('log') {
      steps {
        sh 'ls -la'
      }
    }

    stage('Front End Unit test') {
      steps {
        sh 'cd curriculum-front && npm i && npm run test:unit'
      }
    }

  }
}