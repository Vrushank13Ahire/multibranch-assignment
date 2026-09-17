pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            when {
                branchName 'main'
            }
            steps {
                sh 'echo Running tests'
            }
        }
    }
}
