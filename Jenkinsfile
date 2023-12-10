pipeline{
    agent any 
    stages{
        stage('git checkout'){
            steps{
                 git branch: 'test', url: 'https://github.com/yeshwanth3501/sample_WebApplication.git'
            }
        }
        stage('mavenbuild'){
            steps{
                sh "mvn clean package"
            }
        }
        }
    }
