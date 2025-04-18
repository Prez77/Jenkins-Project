pipeline {
    agent any

    environment {
        BRANCH_NAME = "${env.BRANCH_NAME}"
    }

    stages {
        stage('Run Shell Script') {
            steps {
                sh './deploy.sh'
            }
        }
    }
}
