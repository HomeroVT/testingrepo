pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building in DEVELOP..'
                pwd
                ls -ltrha
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
