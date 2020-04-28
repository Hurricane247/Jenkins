pipeline {
   agent any

   stages {
      stage('hello') {
         steps {
            echo 'Hello, we are defining the steps of continous deployment'
         }
      }
      stage('checkout') {
         steps {
            echo 'Checkout the code from git repository'
         }
      }
      stage('unit-testing') {
         steps {
            echo 'Run unit tests'
         }
      }
      stage('build') {
         steps {
            echo 'Build the code'
         }
      }
      stage('code-quality') {
         steps {
            echo 'Run sonarqube'
         }
      }
      stage('staging') {
         steps {
            echo 'Deploy to staging machines'
         }
      }
      stage('staging-tests') {
         steps {
            echo 'Run staging tests'
         }
      }
      stage('production') {
         steps {
            echo 'Deploy to production machines'
         }
      }
      stage('production-tests') {
         steps {
            echo 'Run production tests'
         }
      }
   }
}
