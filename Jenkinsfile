pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'Step One'
                sh 'Step Two'
            }
        }
        stage('Test') {
            steps {
                sh 'Step Test One'
                sh 'Step Test Two'
            }
        }
        stage('E2E Test') {
            steps {
                sh 'Step E2E Test One'
                sh 'Step E2E Test Two'
            }
        }
    }
    post {
        always {
            echo 'I m in alawys mode'
        }
        success{
            echo 'Success'
        }
        failure{
            echo 'Failed'
        }
    }
}
