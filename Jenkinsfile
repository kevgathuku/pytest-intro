pipeline {

     options { timeout(time: 5, unit: 'HOURS') }

   agent any

   stages {
      stage('Build') {
         steps {
            echo 'Hello Build'
         }
      }
      
      stage('Test') {
         steps {
            echo 'Hello Test'
         }
      }
      
      stage('Deploy') {
         steps {
            echo 'Hello Deploy'
         }
      }
      
      
   }
}
