pipeline {
    agent any

    stages {

        stage('Test') {
            steps {
                sh 'python3 sample.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment successful!'
            }
        }
    }
}