pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sleep 2
        echo 'executing build stage'
        sh 'echo "you can run npm/maven/gradle commands"'
      }
    }

  }
  environment {
    task = 'demo'
    tag = '0.2.4'
  }
}