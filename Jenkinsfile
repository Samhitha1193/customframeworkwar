pipeline {
    agent any 
    stages {
        stage('Build'){
            steps{
              
                bat "docker build . -t custom:${env.BUILD_ID}"
            }
        }
    }
}
