pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				echo 'This is build stage'
			}
		}
		stage('Test'){
			steps{
				echo 'This is test stage'
			}
		}
	}
	post{
		success{
			echo 'I run when pipeline is a success'
		}
		failure{
			echo 'I run when pipeline is a failure!!'
		}
	}
}
