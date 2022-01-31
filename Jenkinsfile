pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build Pipeline'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test Pipeline'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy Pipe'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'visabb786@gmail.com'
    	}

    }
}
