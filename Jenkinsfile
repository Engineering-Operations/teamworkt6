pipeline{
    agent any
    stages{
        stage('1-Blessingstage'){
            steps{
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-id', url: 'https://github.com/Engineering-Operations/teamworkt6.git']]])
            }
        }  
         stage('2-Kaodichistage'){
            steps{
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
            }
        }
          stage('3-Cathystage'){
            steps{
                sh'ps -ef'
                sh 'sudo systemctl status jenkins'
            }
        }
          stage('4-Christianestage'){
            steps{
                sh'ps -ef'
                sh 'sudo systemctl status jenkins'
            }   
        }
    }
}
