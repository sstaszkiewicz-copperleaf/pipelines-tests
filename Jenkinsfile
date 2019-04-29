pipeline {
	agent any

	stages {
		stage('build') {
			steps {
				sh "echo build"
			}
		}
		stage('Test') {
			def myTest = "test"
			steps {
				sh "echo $myTest"
			}
		}
	}
}
