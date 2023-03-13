pipeline {
    agent any
    stages{
        stage("Build"){
            steps{
                echo("Its Build")
                sleep(5)
            }
        }
        stage("Test"){
            steps{
                echo("Its Test")
            }
        }
        stage("Deploy"){
            steps{
                echo("Its Deploy")
            }
        }
    }
    post{
        always{
            echo "I always say hello to you"
        } 
        success {
            echo "Great, succes"
        } 
        failure {
            echo "Oh, its failed"
        } 
        cleanup {
            echo "Don't care its succes or error"
        }
    }
}