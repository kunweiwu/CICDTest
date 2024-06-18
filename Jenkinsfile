pipeline {
    agent any
    stages {
        stage('Verify Ruby') {
            steps {
                sh 'ruby -v'
                sh 'bundler -v'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'java --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}