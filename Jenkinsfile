pipeline {
	agent {label "linux"}
	options {
		disableConcurrentBuilds()
	}
	stages {
		stage('hello') {
			steps {
				echo "hello"
			}
		}
	}
}
