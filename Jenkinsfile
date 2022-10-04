pipeline {
    agent any
    stages {
        stage("verify") {
            sh '''
                docker info
                docker version
                docker compose version
                curl --version
                jq --version
            '''
        }
    }
}