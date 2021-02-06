pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Hello World"
                echo '''
                    "Multiline shell steps works too"
                    dir
                '''
            }
        }
        stage('Second') {
            steps {
                echo "This is to test the update function."
                echo "This is to test the update function."
            }
        }
    }
}
