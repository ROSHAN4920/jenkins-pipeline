pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git main 'https://github.com/ROSHAN4920/jenkins-pipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
