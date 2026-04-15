pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('Run Python') {
            steps {
                sh 'python3 app.py'
            }
        }

    }
}