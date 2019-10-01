pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          bat "javac Hello.java"
          bat "java Hello"
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
  }
}
