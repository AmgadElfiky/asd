pipeline {
    agent any
    stages {
        stage('Terraform Apply') {
            steps {
                script {
                    // Clone your Terraform repository
                    git 'https://github.com/AmgadElfiky/asd/tree/main/terra'
                    // Initialize and apply Terraform
                    sh 'terraform init'
                    sh 'terraform apply -auto-approve'
                }
            }
        }
    }
}
