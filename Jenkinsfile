pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'echo "Eder Test"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }		
		stage('BuildMore') {
            steps {
                sh 'echo "More one step"'
            }
        }
		stage('Test') {
            steps {
                sh 'echo "Test step"'
            }
        }
    }
}
