pipeline {
    agent {
        node{
            label 'maven'
        }
    }
    stages {
        stage('Hello') {
            steps {
                git branch: 'main', credentialsId: 'github', url: 'https://github.com/9kumar21/tweet-trend-new.git'
            }
        }
    }
}