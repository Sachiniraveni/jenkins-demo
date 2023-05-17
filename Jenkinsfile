pipeline{
    agent any

    environment{
        PATH="/opt/maven3"

    }
    stages{
        stage("welcome"){
            steps{
                echo "success"  
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn clean package"
            }
        }
    }
}


