pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'This is the $BUILD_NUMBER bnumber of job $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}