pipeline {
    agent any

    stages {
        stage('K Infra Deployment') {
            steps {
                echo 'K Infra Deployment..'
                which terraform
                sleep 10
            }
        }
        stage('K Infra Validation') {
            steps {
                echo 'Validation..'
                which terraform
                sleep 10
            }
        }
        stage('Deploy FW') {
            steps {
                echo 'Deploying Firewalls....'
                while terraform
                sleep 10
            }
        }
    }
}
