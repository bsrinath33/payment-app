pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                sh ' echo "Hello World" '       
		sh ''' 
		echo "Multistep Script"
		ls -a

		'''
            }
        }
    }
}
