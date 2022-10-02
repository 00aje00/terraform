pipeline {
    agent any
    
    stages {
        stage ('test'){
            steps {
                sh 'echo "hello world"'
                sh 'echo "let today be the beginning of your life"'
            }
        }
        stage ('build'){
            steps {
                sh 'echo "build world"'
            }
        }
        stage ('upload'){
            steps {
                sh 'echo "artifactory world"'
            }
        }

    }
}