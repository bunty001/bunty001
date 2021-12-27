pipeline {
    agent any  

    stages {

        stage('Building') {
            steps { 
                echo 'First Stage- the Code will be now be built into an artifact'
            }
        }
        stage('Artifact Archiving') {
            steps {
                echo 'Second Stage- The Artifact will be uploaded to an artifact repository'
            }
        }
        stage('Testing') {
            steps {
                echo 'Third Stage- The Artifact will be tested in this stage'
            }
        }
        stage('Staging') {
            steps {
                echo 'Forth Stage- The Artifact is staged onto the staging server'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Fifth Stage- The software will now be deployed!'
            }

        }
        stage('Release') {
            steps {
                echo 'Sixth Stage- The Software will be finally release!'
            }
        }
    }
}