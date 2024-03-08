pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Display the build number
                    def buildNumber = currentBuild.number
                    echo "Build Number: ${buildNumber}"

                    // List files in the workspace
                    echo 'List of files in the workspace:'
                    sh 'ls -l'
                }
            }
        }
      
    }
}

