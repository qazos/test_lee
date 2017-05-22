pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/qazos/test_lee', changelog: true, branch: 'qazos-branch', poll: true)
      }
    }
  }
  environment {
    test = 'test'
  }
}