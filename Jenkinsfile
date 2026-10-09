pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from GitHub...'
                // Jenkins automatically handles code checkout when configured via SCM
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Add your build commands here (e.g., sh 'mvn clean package' or sh 'npm run build')
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
                // Add your test commands here (e.g., sh 'npm test')
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add your deployment commands here (e.g., sh 'kubectl apply -f deployment.yaml')
            }
        }
    }
}
