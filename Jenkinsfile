pipeline{
    agent any
    stages {
        stage('Delete the workspace'){
            steps{
                cleanWs()
            }
        }
       stage('second Stage'){
           steps{
               echo "Second stage"
           }
         }
       stage('Third stage'){
           steps{
               echo "Third Stage"
           }
       }
    }   
}
pipeline {
    agent any
    stages {
pipeline {
    agent {label "agentfarm" }
    stages {
   
