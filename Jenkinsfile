pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building in DEVELOP..'
                sh '''#!/bin/bash

                    pwd
                    ls -ltrah
                '''
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
