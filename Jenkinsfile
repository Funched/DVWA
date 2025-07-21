pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // In a real scenario, you'd run build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
                // Here you would run your application's unit tests
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging environment...'
                // This is where you would deploy your application to a test server
            }
        }
    }
}
