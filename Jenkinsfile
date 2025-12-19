pipeline {
    agent any

    stages {

        stage('Welcome') {
            steps {
                echo 'Hello from Pushkar using GitHub'
            }
        }

        stage('System Info') {
            steps {
                sh 'whoami'
                sh 'uname -a'
            }
        }

        stage('Date') {
            steps {
                sh 'date'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
