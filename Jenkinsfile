pipeline {   
    agent any

    stages {   
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "This is sprint1 branch"' 
            }
        }
     
        stage('Testing') { 
            steps { 
               sh 'echo "Testing application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
