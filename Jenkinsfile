pipeline {
	agent any 
	stages {
		stage ('Build') {
			steps {
				sh '''
						echo "This is a Build Stage"
						sleep 2
				
				   '''
			}
		}
	parallel (
		stage ('Deploy_1') {
			steps {
				sh '''
						echo "This is a Deploy Stage"
						sleep 2
				
				   '''
			}
		}
		
		stage ('Deploy_2') {
			steps {
				sh '''
						echo "This is a Deploy Stage"
						sleep 2
				
				   '''
			}
		}
	)
		
		stage ('Test') {
			steps {
				sh '''
						echo "This is a Test Stage"
						sleep 2
				
				   '''
			}
		}
	}
}