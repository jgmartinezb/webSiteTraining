pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                bat 'wmic computersystem get name'
            }
        }
    }
}
