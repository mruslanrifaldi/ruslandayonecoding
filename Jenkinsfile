pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test App'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }

        post {
                always {
                    emailext body: 'TESTING SELENIUM', subject: 'TESTING SELENIUM BY RUSLAN', to: 'selenium15byruslan@gmail.com'
                }
            }
    }
}
