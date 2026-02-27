pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev  Environment'
                sh 'git --version'
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing OK'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production Server'
                sh 'docker --version'
            }
        }
    }
}
