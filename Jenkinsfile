pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo 'This is build $BUILD_NUMBER of demo $DEMO'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}