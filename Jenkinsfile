pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }
    
    stage('Sanity check') {
        steps {
            input "Does the staging environment look ok?"
        }
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
}
