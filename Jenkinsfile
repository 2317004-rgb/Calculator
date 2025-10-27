JENKINFILE

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'javac Calc.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'java Calc'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                echo 'Deployment successful! ✅'
            }
        }
    }
}
