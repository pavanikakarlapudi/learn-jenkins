pipeline {

  agent {
    label 'workstation'
  }

  stages {

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Hello1') {
      steps {
        echo 'Hello World'
      }
    }

   }

  post {
    always {
      echo "sending email"
    }
  }

}