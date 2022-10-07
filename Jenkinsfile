pipeline {
    agent {
        any {
            image 'node:6-alpine'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }

    }
}
