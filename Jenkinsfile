@Library('shared_library') _

pipeline {

  agent { 
    label 'worker_node' 
  }

  stages {

    stage('Install Nginx') {

      steps {
        echo 'Installing Nginx...'
        
        script {
          installnginx() 
        }
        
      }
    }

  }

}
