pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    git branch: 'main', credentialsId: 'your-credentials-id', url: 'https://github.com/your/repository.git'
                }
            }
        }
    }
}
