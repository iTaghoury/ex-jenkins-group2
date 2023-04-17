pipeline {
  agent any
  triggers {
    pollSCM('* 0/2 * ? * * *')
  }
  
  stages {
    stage('Hello') {
      steps {
        echo 'Hello!'
      }
    }
  }
}
