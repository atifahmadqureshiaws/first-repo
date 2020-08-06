pipeline {
    agent {
        node
    }
    stages {
        stage('Startup') {
            steps {
                echo "Hello Starting Bundle"
            }
       }
        stage('In Stage 2') {
            steps {
                echo "Welcome to stage 2"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying to server"
            }
        }
    }
}
