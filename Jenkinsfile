pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Install dependencies (if using Maven)
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                // Run tests (if using Maven)
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                // Deploy to your server or cloud (e.g., AWS, etc.)
                echo 'Deploying application'
            }
        }
    }
}
