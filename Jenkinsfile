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
    stage('stage3') {
      steps {
        build 'test-error-exit'
      }
    }
    stage('stage4') {
      steps {
        build 'test-error-exit'
      }
    }
  }
}