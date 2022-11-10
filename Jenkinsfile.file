pipeline {
    agent {label "maven"}

    stages {
        stage('version') {
            steps {
                sh "mvn --version"
            }
        }
    }
}
