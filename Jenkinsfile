pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            git branch: 'master', credentialsId: 'git', url: https://github.com/megh-6789/JavaApplication.git  
            sh 'pwd'
            }
        }
       }
}
