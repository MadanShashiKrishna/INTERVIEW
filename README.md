# INTERVIEW
pipeline {
	agent any

	stages {

		stage('Build'){
		git 'htt://github.com/repo.git'
		}
		}

	Stage ('Test') {
		steps {
			sh 'echo "Testing.."

		}
		}

	stage ('Deploy'){
	 	steps {
			sh 'echo "Deploy"

			}
			}
			}
