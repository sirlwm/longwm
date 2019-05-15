pipeline {
  agent any
  stages {
    stage('laqudaima') {
      steps {
        git(url: 'https://github.com/sirlwm/longwm.git', branch: 'master')
      }
    }
    stage('mavengoujian') {
      steps {
        sh 'maven clean install'
      }
    }
    stage('xiangmufabu') {
      steps {
        sh 'll'
      }
    }
  }
}