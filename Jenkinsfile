pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
            }
        
        }
        stage("B"){
            steps{
                echo "========executing B========"
            }
        
        }
        stage("C"){
            steps{
                echo "========executing C========"
            }
        
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
