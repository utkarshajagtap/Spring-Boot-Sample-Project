pipeline {
  agent any
  stages {
    stage('Gitcheckout') {
      steps {
        sh '''pipeline {
    agent any
     stages {
        stage(\'Build\') {
            steps {
                git \'git@github.com:utkarshajagtap/Spring-Boot-Sample-Project.git\'
                }
                }
            }
        }'''
        }
      }

    }
  }