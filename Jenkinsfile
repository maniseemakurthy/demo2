pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is build $BUILD_NUMBER for demo $DEMO'
        sh 'echo "This is build $BUILD_NUMBER for demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '2'
  }
}