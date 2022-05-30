pipeline {
	agent any 

	stages() {
		stage('git clone') {
			steps() {
				git 'https://github.com/94jskim/CI-CD_test.git'
			}
		}
	
		stage('Test') {
			steps {
				echo 'Testing..'
			}
		}

		stage('excute sh'){
			steps {
				sh "chmod 744 ./project.sh"
				sh "./project.sh" 
			}
		}
	}
}
