pipeline {
    agent any

    stages {
        stage('Display Jenkins Info') {
            steps {
                script {
                    echo "JENKINS_URL: ${env.JENKINS_URL}"
                    echo "BUILD_ID: ${env.BUILD_ID}"
                }
            }
        }
    }
}
