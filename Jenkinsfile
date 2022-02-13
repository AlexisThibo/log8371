pipeline {

    agent any

    stages {

        stage("build") {

            steps {
                echo 'building the application...'
            }
        }
        stage("test") {

            steps {
                echo 'testing the application...'
                bat './gradlew app:build -x test'
            }
        }
    }
}
