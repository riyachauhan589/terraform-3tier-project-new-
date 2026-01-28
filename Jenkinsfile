
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/riyachauhan589/terraform-3tier-project-new.git'
            }
        }

        stage('Terraform Init') {
            steps {
                sh 'terraform init'
            }
        }

        stage('Terraform Plan') {
            steps {
                sh 'terraform plan'
            }
        }
    }
}
