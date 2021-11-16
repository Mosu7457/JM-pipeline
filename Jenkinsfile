pipeline {
    agent any
    tools {
        maven 'maven'
        git 'Default'
    }
    stages{
        stage( 'Build' ){
            steps{
                sh script: 'mvn clean package'
            }
        }
    }
}
