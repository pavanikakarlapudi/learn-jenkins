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

    stage('Hello2') {
      steps {
        echo 'Hello World'
        mail bcc: '', body: 'Heloo this is a test email ', cc: '', from: '', replyTo: '', subject: 'Test', to: 'raghuk.vit@gmail.com'
      }
    }


  }

  post {
    always {
      echo "sending email"
    }
  }

}