pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Running build automation'
                sh './gradlew build --no-daemon'
                archiveArtifcats artifacts: 'dist/trainSchedule.zip'
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
