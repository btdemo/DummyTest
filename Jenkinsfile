node {
   
   stage('Code Checkout') { 
     git credentialsId: 'githubID', url: 'https://github.com/btdemo/DummyTest.git' 
    }
   stage('Build') {
    withMaven(jdk: 'jdk-1.8', maven: 'maven-3.6') {
     sh 'mvn clean compile'
      }
    }
   stage('Unit Test run') {
    withMaven(jdk: 'jdk-1.8', maven: 'maven-3.6') {
     sh 'mvn test'
      } 
    }
    stage('Deploy to Dev') {
     
    }
   stage('Automation Testing') {
     
    }
   stage('Deploy to Test') {
     
    }
   stage('Smoke Testing') {
     
    }
   stage('Deploy to Prod') {
     
    }
   stage('Acceptance Testing') {
     
    }
}
