pipeline {
  agent any
  stages {
    stage("Build") {
      steps {
        sh "bundle install"
      }
    }
    stage("Test") {
      steps {
        sh "echo 'teste'"
      }
    }
  }
}
