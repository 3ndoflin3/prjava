
pipeline {
    agent any
     environment {
        FICHERO = "Simple.java"
        NOMBRE = "Simple"
    }

    stages {
        stage('Compilar fichero') {
            steps {
                sh 'javac ${FICHERO}'
            }
        }
        stage('Ejecutar fichero') {
            steps {
                sh 'java ${NOMBRE}'
            }
        }
    }
}
