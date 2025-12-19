pipeline{
    
    agent any
        
        stages{
            stage('checkout')
            {
                steps{
                    git branch: 'feature1', url: 'https://github.com/deekshit636/c-proj-repo.git'
                }
            }

            stage('build'){

              steps{
                sh '''
                        mvn clean package
                '''
              }
            }
            
        }

}
