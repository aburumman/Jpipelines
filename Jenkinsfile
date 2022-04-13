pipeline {
	agent any 
	stages {
		stage("build") {
			steps{
				echo "building the application"
			}
		}
		stage("test") {
			steps {
				echo "testing the application"
				sh 'ls -alh'
			}
		}
		stage("deploy"){
			steps {
				echo "Deploying the application"
			}
		}
		}
}