pipeline {
    agent any

    stages {
        stage('K Infra Deployment') {
            steps {
                echo 'K Infra Deployment..'
                sh '/usr/bin/terraform --help'
                sleep 10
            }
        }
        stage('K Infra Validation') {
            steps {
                echo 'Validation..'
                sh '/usr/bin/terraform --help'
                sleep 10
            }
        }
        stage('Deploy FW') {
            steps {
                echo 'Deploying Firewalls....'
                sh '/usr/bin/terraform --help'
                sleep 10
            }
        }
        stage('K Service Deployment') {
            steps {
                echo 'K Service Deployment....'
                sh '/usr/bin/terraform --help'
                sleep 10
            }
        }
        stage('Python Test Framework') {
            steps {
                echo 'Python Test Framework...'
                sh '/usr/bin/terraform --help'
                sleep 10
            }
        }
    }
}
