pipeline{
    agent any
    stages{
        stage('Build Image'){
            steps{
                script{
                    dockerapp = docker.build("eliasdosreis/api-produto:", '-f ./src/Dockerfile ./src')
                }
            }
        }
    }
}
