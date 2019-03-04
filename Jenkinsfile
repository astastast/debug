pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo 'hi'
      }
    }
    stage('2') {
      steps {
        addInfoBadge(text: 'bag1', id: '1')
      }
    }
    stage('3') {
      steps {
        addBadge(icon: 't', text: 'tt')
      }
    }
  }
  environment {
    val = 'val'
  }
}