pipeline {
agent none
 
  stages {
    stage('abc'){
      
      steps {
        sh "kubectl  apply -f  deploy.yml  --kubeconfig  /admin.conf"
      }
    }
  }
}
