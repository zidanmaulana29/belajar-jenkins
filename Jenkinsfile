pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/user/repo.git'
            }
        }
        stage('Run') {
            steps {
                sh './agent.sh'
            }
        }
    }
}
