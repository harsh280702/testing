pipeline{
    agent any
    stages{


         stage("compile"){          
           steps{
             sh 'java Test.java'
           }
         }
         stage("run")
         {
           steps{
              sh 'java Test'
           }
         }
         
    }
}