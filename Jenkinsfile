pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          bat "javac Hello.java"
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {

          bat "java Hello"
          bat "javac Hello2.java"
        }
      }
    }
    stage('Stage 3'){
      steps{
        echo "This is stage 3"
        bat "java Hello2"
 
      }
    }
  }

