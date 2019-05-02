pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        build 'test2-pipeline'
      }
    }
    stage('stage2') {
      steps {
        echo 'stage'
      }
    }
  }
}