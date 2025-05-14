pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Pulls code from the repository
                git branch: 'main', url: 'https://github.com/TejasMore09/jenkins-basic-task2.git'
            }
        }
        stage('Build') {
            steps {
                // Replace with your build commands, e.g., for Node.js
                sh 'echo "Running build step"'
                sh 'npm install || true' // Example: Install dependencies (|| true to avoid failure if not Node.js)
            }
        }
        stage('Test') {
            steps {
                // Replace with your test commands
                sh 'echo "Running tests"'
                sh 'npm test || true' // Example: Run tests
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Check logs for details.'
        }
    }
}
