pipeline {
    agent any
    stages {
        stage('building master bracnh') {
            when {
                branch 'master'
            }
            steps {
                echo 'building master step'
            }

        }
        stage('building dev branch') {
            when {
                branch 'dev'
            }
            steps {
                echo 'building dev step'
            }

        }
    }
}
