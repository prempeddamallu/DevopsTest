pipeline{
    agent any 
    stages{
        stage('Run python file'){
            steps{
                script{
                    sh "python3 app.py"
                }
            }
        }
        stage('END'){
            steps{
                script{
                    echo "Success"
                }
            }
        }
    }
}
