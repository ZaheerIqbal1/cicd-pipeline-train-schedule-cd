pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
