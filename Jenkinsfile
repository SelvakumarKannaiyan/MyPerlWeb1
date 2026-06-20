pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git branch: 'main', credentialsId: 'Mytest1', url: 'https://github.com/SelvakumarKannaiyan/MyPerlWeb1.git'
            }
        }
        stage('plprint') {
            steps {
                bat 'perl print.pl'
            }
        }
    }
}
