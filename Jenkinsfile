node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	post{
		success{
			echo 'I run when pipeline is a success'
		}
		failure{
			echo 'I run when pipeline is a failure'
		}
	}
}
