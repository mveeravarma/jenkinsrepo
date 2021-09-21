pipeline{
   agent any
    stages{
        stage('checkout'){
            
            steps{
                echo "git stage"
            }
        }
        stage('maven build'){
            steps{
                
                echo "mvn stage"
            }
        }
       stage('deploy'){
           steps{
               echo "deploy to dev"
           }
       } 
    }
    
}
