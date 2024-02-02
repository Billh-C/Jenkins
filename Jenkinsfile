pipeline {
  agent any
  stages {
    stage(‘Stage One'){
    steps {
      sh "ls"
      sh "pwd"
    }
  }
  stage(‘Stage Two'){
    steps {
      sh “touch newFile.txt"
    }
  }
  stage('Deploy'){
    steps {
    }
  }
}
