    pipeline {
        agent any // Specifies where the pipeline will run (e.g., on any available agent)

        stages {
            stage('Build') {
                steps {
                    echo 'Building the application...'
                    // Add your build commands here, e.g.,
                    sh 'mvn clean install'
                }
            }
            stage('Test') {
                steps {
                    echo 'Running tests...'
                    // Add your test commands here, e.g.,
                    sh 'mvn test'
                }
            }
            stage('Deploy') {
                steps {
                    echo 'Deploying the application...'
                    // Add your deployment commands here, e.g.,
                     sh 'echo hello world!!!'
                }
            }
        }            
                        
    }
