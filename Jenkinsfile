// This is my 1st jenkins file
pipeline {
	agent {
	label "slave-2"
	}
	stages {
		stage ('deploy-index') {
		steps {
			sh "cp -r index.html /var/www/html/"
			}
		}
		stage ('2023Q3') {
			steps {
			echo "This is my 2023Q3 branch"
			}
		}
	}
}
