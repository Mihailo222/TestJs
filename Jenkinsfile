pipeline {

	agent any

	stages {

		stage(“build”) {
	
		steps {
                     echo 'This is a building step'
		      }
		}

		stage("test"){
			steps {
				echo 'This is a test step.'
			}
		}

		stage('deploy'){
			steps {
				echo 'Step while deploying.'
			}
		}
	
	} 

}

node {

}
