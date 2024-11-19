pipeline{
    agent any 
    stages{
        // stage('Build'){
        //     steps{
                
        //         git checkout
                
        //     }
        // }
        stage('uild'){
            steps{
                script{
                    sh "python3 app.py"
                }
            }
        }
        stage('Bui'){
            steps{
                script{
                    echo "Deploying"
                }
            }
        }
    }
}
