pipeline {
    agent any
    triggers 
       
    
    stages {
        stage('vcs') {
            steps {
                git branch: 'main', url: "https://github.com/Syedsuhaan/saleor-dashboard.git"
            }
        }
        stage('docker image build') {
            steps {
                sh 'docker image build -t syeed/saleor-dashboar:DEV .'
            }
        }
        

    

    }
  }
    
