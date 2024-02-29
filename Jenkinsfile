pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npx vite build'
                sh 'cp -rf dist/* /home/mykola/www'
            }
        }
    }
}