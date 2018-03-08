pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo 'hello'
      }
    }
    stage('stage 2') {
      steps {
        build 'stage_compile'
      }
    }
  }
}