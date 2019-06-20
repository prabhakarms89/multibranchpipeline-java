pipeline {
  agent any
  stages {
    stage('SCM checkout') {
      steps {
          echo "get the Prime.java code from master branch github"
          sh 'javac -d . src/*.java'
      }
    }
  }
}
