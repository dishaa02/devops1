pipeline {

    agent any

    stages {

        stage('Build') {

            steps {

                sh 'mvn clean package'

            }

        }

        stage('Test') {

            steps {

                sh 'pytest tests.py'

            }

        }

        stage('Deploy') {

            steps {

                sh 'ssh user@server "docker deploy myapp"'

            }

        }

    }

}
