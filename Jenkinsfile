This is my 1st jenkins file
pipeline {
	agent {
	label "built-in"
	}
	stages {
		stage ('deploy-index') {
		steps {
			sh "cp -r index.html /var/www/html/"
			sh "chmod -R 777 /var/www/html"
			}
		}
		stage ('2023Q1') {
			steps {
			echo "This is my 2023Q1 branch"
			}
		}
	}
}
