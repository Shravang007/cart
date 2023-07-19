pipeline {
 agent {
 node { label 'workstation'}
 }

 stages {

 stage('Code Checkout') {
      steps {
         echo 'Code Checkout'
      }
 }
 stage('Built') {
       steps {
          echo 'Built'
       }
  }
  stage('Unit Tests') {
        steps {
           echo 'Unit Tests'
        }
   }
   stage('Code Analysis') {
         steps {
            echo 'Code Analysis'
         }
    }
    stage('Security Scans') {
          steps {
             echo 'Security Scans'
          }
     }
     stage('Publish a Artifact') {
           steps {
              echo 'Publish a Artifact'
           }
      }
 }
}
