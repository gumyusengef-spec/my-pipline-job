pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building the project..."
                bat 'dir'   // For Windows agents; change to sh 'ls -la' for Linux
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }

    }
}
