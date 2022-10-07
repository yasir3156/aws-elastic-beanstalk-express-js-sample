pipeline {
    agent {
        any {
            image 'node:6-alpine'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'apt instsll npm'
                sh 'npm install --save'
            }
        }

    }
}
