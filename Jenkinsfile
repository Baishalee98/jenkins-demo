pipeline{
	agent any
	environment{
		GO111MODULES = 'off'
	}
	tools{
		go 'go-1.17'
	}
	stages{
		stage('Build'){
			steps{
				sh 'go build'
			}
		}
	}
}
