pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        sh 'echo "Build 1 "'
      }
    }

    stage('GIT_sync') {
      steps {
        git(url: 'https://github.com/rupin147/jenkin_test', branch: 'main', changelog: true)
      }
    }

  }
}