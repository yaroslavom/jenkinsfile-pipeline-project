pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Welcome to Jenkins'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}