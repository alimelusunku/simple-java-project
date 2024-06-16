pipeline {
    agent any

    stages {
        stage('git') {
            steps {
                git ( url:"https://github.com/alimelusunku/simple-java-project",
                      branch: "master"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
