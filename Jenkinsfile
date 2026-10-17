pipeline {
    agent any
    stages {
        stage ('Mmaven Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
