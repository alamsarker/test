pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Auto Builing...'
            }
        }
        stage('Test') {
            steps {
                sh 'ls -l'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying after PR...'
            }
        }
    }
}
