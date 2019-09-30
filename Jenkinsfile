pipeline {
    agent any
    stages {
        stage('Compile'){
            steps {
                sh 'chmod +x ./gradlew'
                sh "./gradlew compileJava"
            }
        }
        stage('Test') {
            steps{
                sh './gradlew test'
            }
        }
    }
}