pipeline {
    // agent {
    //     docker {
    //         image 'node:lts-buster-slim'
    //         args '-p 3000:3000'
    //     }
    // }
    agent any

    // environment {
    //     CI = 'true'
    // }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
