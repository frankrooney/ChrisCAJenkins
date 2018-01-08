pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                bat '-B -DskipTests clean package'
            }
        }
        stage('Test'){
            steps {
                bat 'mvn test'
            }
        }
    }
}
