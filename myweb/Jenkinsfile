pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('hello') {
            steps {
                sh 'python3 manage.py $X_VALUE $Y_VALUE'
            }
        }
    }
}

