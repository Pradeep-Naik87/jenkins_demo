pipeline{
    agent any
    stages{
        stage("checkout"){
            steps{
                git "https://github.com/Pradeep-Naik87/jenkins_demo.git"
            }
        }
        stage("compile"){
            steps{
            sh "mvn clean compile"
            }
        }
        
         stage("package"){
            steps{
            sh "mvn package"
            }
        }
       
        }
   
}
