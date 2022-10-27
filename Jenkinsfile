pipeline {
	agent{label "linux"}
	options {
		buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numtoKeepStr: '5')
		disableConcurrentBuilds()
	}
	stages {
		stage('hello'){
			step {
				echo "hello"
			}
		}
	}
}
