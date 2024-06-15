pipeline {
    agent any

    stages {
        stage('Hello1') {
            steps {
                sh '''
                uname
                pwd
                ls
                '''
            }
        }

        stage('Hello2') {
            steps {
                sh '''
                uname
                pwd
                ls
                '''
            }
        }

        stage('Hello3') {
            steps {
                sh '''
                uname
                pwd
                ls
                ls -l
                '''
            }
        }


    }
       
}