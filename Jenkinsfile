pipeline {
    agent any

    stages {
        stage('hello world') {
            steps {
                 git branch: 'main', credentialsId: 'gitcred', url: 'https://github.com/vcguedes/pythoncode.git'
            }
        }
        stage('Build') {
            steps {
                echo "build in this project"
            }
        }
    }
}
