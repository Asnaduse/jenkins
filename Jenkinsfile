pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'mvn clean package'  // Example for Java projects
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'mvn test'  // Run unit tests
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
