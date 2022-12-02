pipeline {
    agent any 
    stages {
        stage('Build master') {
            when {
                branch 'main'
            }
            steps {
                echo 'Building master'
            }
        }
        stage('Build Dev') {
            when {
                branch 'dev'
            }
            steps {
                echo 'Building dev'
            }
        }
    }
}
