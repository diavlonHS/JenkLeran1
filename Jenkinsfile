pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }
        
    stages {
        
        stage('Sanity check') {
           steps {
             input "Does the staging environment look ok?"
           }
        }
                
        stage('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
}
