pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                git 'https://github.com/shazforiot/HelloWorld-Springboot-App.git'
            }
        }
        stage('Maven build'){
            steps{
                sh 'mvn package'
            }
        }     
    }
}
