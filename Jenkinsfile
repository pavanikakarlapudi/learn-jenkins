pipeline {

  agent {
     label 'ansible'

       }

stages {

   stage('hello')  {
        steps {
          echo 'elloworld'
                 }
                    }
                           }

   stage('hello1')  {
        steps {
          echo 'helloworld jenkins'
                 }
                    }
                           }


   stage('hello2')  {
        steps {
          echo 'helloworld'
                 }
                    }
                           }

 stage('Hello2') {
      steps {
        echo 'Hello World'
        mail bcc: '', body: 'Heloo this is a test email ', cc: '', from: '', replyTo: '', subject: 'Test', to: 'pavanikakarlapudi1990@gmail.com'
      }
    }

    post {
       always {
         echo "sending email"
       }
     }
        }

@Library('roboshop') _
 test()