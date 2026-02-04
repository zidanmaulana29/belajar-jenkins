pipeline {
    agent { label 'linux java17' }

    stages {
        stage('menjalankan script pada jenkins agent') {
            steps {
                sh '''
                  cd /home/idanzi/jenkins/praktik
                  ./agent.sh
                '''
            }
        }
    }
}
