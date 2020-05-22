pipeline {
  agent any
  stages {
    stage('2') {
      parallel {
        stage('2') {
          steps {
            git(url: 'https://github.com/waterwaterwater/bfuse.git', branch: 'master', changelog: true)
          }
        }

        stage('2a') {
          steps {
            echo 'kuku'
          }
        }

      }
    }

    stage('3') {
      steps {
        echo 'git clone'
      }
    }

  }
  environment {
    first = '1'
  }
}