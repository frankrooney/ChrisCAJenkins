pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test'){
            steps {
                bat 'mvn test'
            }
        }
    }
}
