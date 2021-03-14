pipeline {
    agent {label 'master'}

    stages {
        stage('load') {
            steps {
                script {
                    load 'Jenkinsfile.detail'
                }
            }
        }
    }
}
