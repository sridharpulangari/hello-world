pipeline {
    agent any 
    stages {
        stage('Check Out') {
           
                steps {
                 checkout scm 
            }
          }
       stage('Build'){

           steps {
             echo 'mvn clean package'
           }
      }
       stage('Deploy'){

           steps {
              echo 'mvn clean deploy'       

             }
          }
       stage('Notification'){

           steps {
             echo 'notification'

             }
          }

        
    }
}
