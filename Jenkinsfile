pipeline {
  agent any
  stages {
    stage('SCM checkout') {
      state {
          echo "get the Prime.java code from master branch github"
          sh 'javac -d . src/*.java'
      }
    }
  }
}
