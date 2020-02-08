pipeline{
	agent any
	options {
		skipDefaultCheckout(true)
	}
	stages {
		stage('Build Preparation') {
			steps {
				echo 'Starting Build Preparation'
				script {
					scm checkout
				}
				echo 'Completed Build Preparation'
			}
		}
		stage ('Build Components'){
			steps{
				echo "build components"
			}
		}
	}
}