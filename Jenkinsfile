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
          bat "javac Hello.java"
          bat "java Hello"
        }
      }
    }
  }
}
