pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
        MYSQL_CREEDS = credentials('mysql-guudnberg')
    }
        
    stages {
        
              
        stage('Build') {
            steps {
                sh 'printenv'
                sh 'echo $MYSQL_CREEDS'
                sh 'echo $MYSQL_CREEDS_USR'
                sh 'echo $MYSQL_CREEDS_PSW'
            }
        }
    }
}
