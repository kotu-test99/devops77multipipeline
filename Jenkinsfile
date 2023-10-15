pipeline {   
    agent any

    stages {   
        stage('master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
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
