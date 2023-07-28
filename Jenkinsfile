pipeline {
  agent {
    node {
      label 'Node-Ritesh'
    }

  }
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/riteshakadu/php-demo.git', branch: 'main')
      }
    }

    stage('Build Code') {
      steps {
        sh 'php --version'
      }
    }

  }
}
