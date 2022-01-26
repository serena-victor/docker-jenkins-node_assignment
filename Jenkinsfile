pipeline {
	agent any  

	stages {
		stage('Build Docker') {
			steps {
				bat 'docker compose up'
			}
		}
	}
}