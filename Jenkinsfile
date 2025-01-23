pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/kien12345kien/jenkins.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add build commands here (e.g., `mvn clean install` or `npm install`)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., `mvn test` or `npm test`)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment commands here
            }
        }
    }
}
