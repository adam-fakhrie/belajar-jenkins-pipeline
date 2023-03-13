pipeline {
    stages{
        stage("Hello"){
            steps{
                echo("Hello pipeline")
            }
        }
    }
    post{
        always{
            echo "I always say hello to you"
        } success {
            echo "Great, succes"
        } failure {
            echo "Oh, its failed"
        } cleanup {
            echo "Don't care its succes or error"
        }
    }
}