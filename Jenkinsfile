/*
//SCRIPTED
node {
		echo "Build"
		echo "Test"
		echo "Integration Test"
	
}
*/

//DECLARATIVE

pipeline {
	// agent : where your build is going to run agent is similar to node but agent give you a lot of flexibility
	agent any 
	// we can't have pipeline without any stages
	stages{
		stage('Build'){
			steps {
				echo "Build"

			}
		}
		stage('Test'){
			steps {
				echo "Test"
			}
		}
		stage('Integration Test'){
			steps {
				echo "Integration Test"
			}
		}
	}
}