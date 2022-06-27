pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source codesssssss'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java codesssssssss.'
                sh 'java Hello'
            }
        }
    }
}