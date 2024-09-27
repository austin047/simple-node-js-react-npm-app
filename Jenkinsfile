pipeline {
    agent any


    tools  { nodejs "node"}
    stages {
        stage('Build') { 
            steps {
                nodejs(nodeJSInstallationName: 'node20') {
                    sh 'npm -v' 
                    sh 'node -v'
                    sh 'npm install' 
                }
            }
        }
    }
}
