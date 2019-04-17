pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/urraji/MyRepo.git', branch: 'master', credentialsId: 'urraji')
      }
    }
    stage('Done') {
      steps {
        echo 'Its done'
      }
    }
  }
}