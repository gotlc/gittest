pipeline {
    agent any
    
    environment{
        PATH="/usr/local/jdk1.8.0_201"
    }
    
    tools{
        maven 'mvn-3.5.4'
    }
    
    stages{
    stage("Bulid"){
        steps{
            sh "mvn clean package spring-boot:repackage"
            sh "printenv"
         }
        
    }
    }
}
