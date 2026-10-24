pipeline{
        agent any 
        stages{
          stage('Package'){
            steps{
             sh 'mvn package'
              echo "installed the package"
          }
        }   
        stage('Run build'){
          steps{
            sh 'java -jar target/java-project2-1.9.jar'
          }
        }
     }   
               
