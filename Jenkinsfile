pipeline {
    agent any
    
        stages{
            stage("restore dependendies"){
           steps{
            bat 'dotnet restore'
           } 
        }

        stage("build the project"){
           steps{
            bat 'dotnet build'
           } 
        }

         stage("run the tests"){
           steps{
            bat 'dotnet test'
           } 
        }
        }
}
