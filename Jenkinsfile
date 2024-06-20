pipeline {
    agent any
    tools {
                nodejs "node"
            }
    stages {
        stage('Build') { 
            steps {
                sh 'echo $PATH'
                sh 'npm install' 
            }
        }
    }
}