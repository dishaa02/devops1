pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package' // Replace with your build command
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test' // Replace with your test command
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...' // Add actual deployment steps here
            }
        }
    }
}
