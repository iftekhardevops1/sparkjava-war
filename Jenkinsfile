pipeline {
	agent any
	environment {
		PATH:"/opt/maven/bin:$PATH"
	}
	stages {
		stage ('build') {
			stage {
			sh 'mvn clean package'
			}
		}
	}
}

