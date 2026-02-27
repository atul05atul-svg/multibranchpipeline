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
        stage('Deploy') {
            steps {
                echo 'I am in Deploying'
                sh 'kubectl version --client'
            }
        }
        stage('Monitoring') {
            steps {
                echo 'I am in Monitoring'
                sh 'helm version'
            }
        }
        stage('Security') {
            steps {
                echo 'I am in Security'
                sh 'trivy --version'
            }
        }
        stage('Performance') {
            steps {
                echo 'I am in Performance Testing'
                sh 'jmeter --version'
            }
        }
            stage('Rollback') {
                steps {
                echo 'I am in RollBack'
                sh 'jmeter --version'
            }
    }
}
