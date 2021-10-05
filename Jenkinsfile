pipeline {
    agent any

    environment {
        PROJECT_NAME = "Neptun"
        OWNER_NAME = "SSHMIDT"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Start'
                echo 'Building'
                echo "PR ${PROJECT_NAME}"
                echo "OW ${OWNER_NAME}"
                echo 'End'
            }
        }
    

        stage('Test') {
            steps {
                echo 'Start'
                echo 'Testing'
                echo 'End'
            }
        }
    

        stage('Deploy') {
            steps {
                echo 'Start'
                echo 'Deploying'
                echo 'End'
            }
        }
    }
}
