pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/chanakyaboyini/demo-counter-app.git'
                }
            }
            stage('Unit Testing'){
            
            steps{
                
                sh 'mvn test'
        }
    }
}
