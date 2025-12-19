pipeline{
    
    agent any
        
        stages{
            stage('checkout')
            {
                steps{
                    git url: 'https://github.com/deekshit636/c-proj-repo.git'
                }
            }

		stage('dummy'){
			steps{
				echo "Hello dummy"
			}
		}	           
        }

}
