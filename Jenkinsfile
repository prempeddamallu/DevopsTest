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
                    sh "python app.py"
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
