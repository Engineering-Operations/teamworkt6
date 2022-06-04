Pipeline {
    agent any
    stages{
        stage('1-Blessingstage'){
            steps{
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-id', url: 'https://github.com/Engineering-Operations/teamworkt6.git']]])
            }
        }
    
    }
}