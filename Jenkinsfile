pipeline{
	agent { docker {image 'alpine' } }
//	environment {
//		dockerHome = tool 'mydocker'
//		PATH = "$dockerHome/bin:$PATH"
//	}
	
	stages{
		stage('Build'){
			steps{
				echo 'This is build stage'
				sh 'docker --version'
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
