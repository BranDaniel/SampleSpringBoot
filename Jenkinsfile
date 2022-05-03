pipeline{
    agent any
    stages{
        stage('Git Clone'){
            steps{
                git 'https://github.com/BranDaniel/SampleSpringBoot.git'
            }
        }
        stage('Maven Test'){
            steps{
                bat 'mvn test'
            }
        }        
        stage('Maven Deploy'){
            steps{
                echo "Deploying the war file to the server"
            }
        }        
    }
}
