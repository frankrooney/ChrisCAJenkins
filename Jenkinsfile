pipeline {
    agent any
    stages {
        stage('Compile') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}
