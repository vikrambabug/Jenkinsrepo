pipeline {
    agent any   // run on any available Jenkins agent

    stages {
        stage('Check Node') {
            steps {
                echo "This build is running on: ${env.NODE_NAME}"
            }
        }
        
        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the project..."
            }
        }

        stage('Delivery') {
            steps {
                echo "Delivering the project..."
            }
        }
        
	stage('Deployment') {
            steps {
   
                 echo "Deployment is happened in this pipeline"
            }
         }
}

}

