pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'set'
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}