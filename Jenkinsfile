pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is build $BUILD_NUMBER for demo $DEMO'
        bat 'echo "This is build $BUILD_NUMBER for demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '2'
  }
}