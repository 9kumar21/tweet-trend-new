pipeline {
    agent {
        node{
            label 'maven'
        }
    }
    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/9kumar21/tweet-trend-new.git'
            }
        }
    }
}