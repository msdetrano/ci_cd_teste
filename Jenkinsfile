pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/seu-repo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Compilando o projeto..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Rodando testes..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Fazendo deploy..."'
            }
        }
    }
}
