pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
              echo "Building Artifact"
              echo "testing"
           }
       }
      stage('Deploy Code') {
          steps {
               sh "echo "Deploying Code"
          }
      }
      stage('3-testing codes'){
        step{
            sh 'lscpu'
        }
      }
   }
}