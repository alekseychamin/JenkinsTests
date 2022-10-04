pipeline {
    agent any
    stages {
        stage("verifing") {
            steps {
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
}