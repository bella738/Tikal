pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/bella738/Tikal.git', branch: 'master', poll: true)
      }
    }

    stage('') {
      steps {
        echo 'hi'
      }
    }

  }
}