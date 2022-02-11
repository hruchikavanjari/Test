pipeline {
    agent any
    
    stages {
        stage('git pull') {
            steps {
                bat 'git pull origin master'            
            }
        }
    
   
       stage('yarn') {
            steps {
                bat 'yarn' 
                
            }
        }
        
        stage('yarn build') {
            steps {
                bat 'yarn build:production' 
                
            }
        }
     
    }
}
