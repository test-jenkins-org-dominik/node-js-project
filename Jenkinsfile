pipeline {
    agent none
    stages {
        stage('Node install') { 
            agent { label 'u20-nodejs16-yarn' }
            steps {
                sh 'npm install' 
            }
        }
    }
}
