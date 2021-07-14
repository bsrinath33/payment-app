pipeline {
    agent any
    stages{
        stage('Sample'){
            steps{
                sh ' echo "Hello World" '       
		
		sh ''' 
		echo "Multistep Script----SRINATH"
		
		ls -ai

		'''
            }
        }
	stage('Mvn Build'){
	steps{
	     sh 'mvn install'
	}
	
	}
    }
}
