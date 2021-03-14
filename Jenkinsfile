pipeline {
    agent {label 'master'}

    stages {
        stage('Hello World') {
            steps {
                script {
                    def util = load 'util.groovy'
                    def message = util.getMessage()
                
                    sh "echo '${message}'"
                }
            }
        }
    }
}
