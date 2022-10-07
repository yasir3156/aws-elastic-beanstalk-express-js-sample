pipeline {
    agent {
        any {
            // Use Node 16 Docker image as the build agent
            image 'node:16-alpine'
        }
    }
    stages {
        // build step that runs the command `npm install --save`
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }
    }
}
