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
            bat "C:\D\apache-maven-3.8.4-bin\apache-maven-3.8.4\bin\mvn clean compile"
            }
        }
        
         stage("package"){
            steps{
            bat "C:\D\apache-maven-3.8.4-bin\apache-maven-3.8.4\bin\mvn package"
            }
        }
       
        }
   
}
