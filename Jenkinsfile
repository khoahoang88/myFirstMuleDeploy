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
		stage('cat README') {
			when {
				branch "fix-*"
			}
			steps {
				sh '''
					cat README.md
				'''
			}
		}
	}
}
