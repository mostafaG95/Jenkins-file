pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/mostafaG95/jenkins/blob/main/Jenkinsfile',
                branch: 'main'

                // Run Maven on a Unix agent.
                sh "ls"

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }

            }
        }
    }
