pipeline {
    agent any

    stages {
        stage('K Infra Deployment') {
            steps {
                echo 'K Infra Deployment..'
                sleep 60
            }
        }
        stage('K Infra Validation') {
            steps {
                echo 'Validation..'
                sleep 30
            }
        }
        stage('Deploy FW') {
            steps {
                echo 'Deploying Firewalls....'
                sleep 5
            }
        }
    }
}
