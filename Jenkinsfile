pipeline {
    agent any  // Use any available agent for this pipeline

    stages {
        stage('Breakfast') {
            steps {
                echo "im doing breakfast"
            }
        }
        
        stage('workout') {
            steps {
                
                echo 'i am doing workout'
                
            }
        }
        
        stage('study') {
            steps {
                // Run unit tests
                echo 'i am studying'
               
            }
        }
        
        stage('family time') {
            steps {
                // Package the application
                echo 'spending time with family'
               
            }
        }
        
        stage('play') {
            steps {
                // Deploy the application
                echo 'playing with friends'
               
            }
        }
    }

    post {
        always {
            // Steps that always run, e.g., cleanup or notifications
            echo 'Pipeline completed!'
        }
        success {
            echo 'my day went well'
        }
        failure {
            echo 'my day not spent well'
        }
    }
}

