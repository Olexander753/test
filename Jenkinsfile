pipeline {
    agent { dockerfile true }
    stages {
        stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
} 
}
