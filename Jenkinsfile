pipeline {

	agent any

	stages {

		stage(“build”) {
	
		steps {
                     echo 'This is a building step'
		      }
		steps {
		    echo 'This is step 2 of building stage.'
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
