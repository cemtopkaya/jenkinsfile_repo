pipeline {
    agent any 
    stages {
        stage('Checkout external proj') {
            steps {
                git branch: 'master',
                    url: 'ssh://git@github.com:cemtopkaya/jenkinsfile_repo.git'
                sh "ls -lat"
            }
        }
        stage('Build') { 
            steps {
                echo "build step"
            }
        }
        stage('Test') { 
            steps {
                echo "test step"
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy step"
            }
        }
    }
}
