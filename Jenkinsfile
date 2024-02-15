pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hell') {
            steps {
                echo 'Hello'
            }
        }
        stage('Helo') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always{
            emailext body: '', subject: '', to: 'amankr18042000@gmail.com'
        }
    }
}
