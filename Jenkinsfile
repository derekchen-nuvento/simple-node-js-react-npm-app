pipeline {
    agent any
    tools {
                nodejs "Nodejs"
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