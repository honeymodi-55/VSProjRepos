pipeline {
    agent any {
        stages {
            stage ('compliling Java program')
            {
                steps {
                    sh 'javac SimpleJava.java'
                }
            }
            stage ('Running Java program')
            {
                steps {
                    sh 'java HelloWorld'
                }
            }
        }
    }
}