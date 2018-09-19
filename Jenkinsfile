pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh "echo $WORKSPACE"
        sh 'docker build -t registry.cn-hangzhou.aliyuncs.com/franktest/kube-app:1 .'
      }
    }
  }
}
