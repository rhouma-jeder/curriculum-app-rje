pipeline {
  agent any
  stages {
    stage('Check out ') {
      steps {
        git(url: 'https://github.com/rhouma-jeder/curriculum-app-rje', branch: 'master')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}