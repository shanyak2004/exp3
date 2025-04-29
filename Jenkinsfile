pipeline {
    agent any
    stages {
        stage("Clone") {
            steps {
                git branch: 'main', url: 'https://github.com/shanyak2004/exp3.git'
            }
        }
        stage("Deploy") {
            steps {
                script {
                    bat "copy index.html C:\\xampp\\htdocs\\index.html"
                }
            }
        }
    }
}
