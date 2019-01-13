	node {
		agent any

		stages {
		    stage('Checkout') {
		        steps {
				git 'https://github.com/Suresh498/gamutkart.git'
					
		        }
		    }
			stage('Build') {
		        steps {
					sh 'mvn install -DskipTests'
		        }
			}
			stage('Test') {
		        steps {
					sh 'mvn test'
		        }
			}
		}
	}
