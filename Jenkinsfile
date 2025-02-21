pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Jayanka-J/IBM_PROJECT.git']])
            }
        }
         stage('Docker') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Jayanka-J/Resume-Builder.git']])
            }
        }
        stage('Kubernetes') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Jayanka-J/Resume-Builder.git']])
            }
        }
        stage('Final') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Jayanka-J/Resume-Builder.git']])
            }
        }
    }
}
