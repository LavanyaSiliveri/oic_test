pipeline{

    agent any

    stages {

        stage("build"){

            steps {
                echo 'building'
            }
        }

        stage("deploy"){

            steps {
                echo 'deploying'
            }
        }
    }
    post {
        always {

            //Email after the deployment
        }
        failure {
            //Email if deployment failed
        }
    }
}