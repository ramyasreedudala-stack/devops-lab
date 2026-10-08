pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/ramyasreedudala-stack/devops-lab.git'
      }
    }
    stage('Build') {
      steps {
        bat 'echo Build completed"
      }
    }
    stage('Test') {
      steps {
        bat 'echo Tests passed'
      }
    }
  }
}
