pipeline {
    agent any
    stages {
        stage('build a') {
            when {
                changeset "**/a/*.*"
            }
            steps {
                echo 'building a'
            }
        }
        stage('build b') {
            when {
                changeset "**/b/*.*"
            }
            steps {
                echo 'building b'
            }
        }
          stage('build c') {
            when {
                changeset "**/c/*.*"
            }
            steps {
                echo 'building c'
            }
        }
    }
}