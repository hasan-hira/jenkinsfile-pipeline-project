pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source codeEEEEEEEEE'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java codeEEEEEEEEE.'
                sh 'java Hello'
            }
        }
    }
}