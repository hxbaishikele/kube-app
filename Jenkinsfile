pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'docker build -t registry.cn-hangzhou.aliyuncs.com/franktest/kube-app:$BUILD_NUMBER .'
      }
    }
  }
}