pipeline {
	agent any

  environment {
		VERSION = '0.0.1'
	}

	stages {
		stage('Deploy') {
			steps {
        // wget o curl
				bat 'copy D:\\devenv\\Maven\\repository\\bootcamp\\jenkins\\war-example\\' + env.VERSION + '\\war-example-' + env.VERSION + '.war D:\\devenv\\CURSO-GIT-PRUEBAS\\apache-tomcat-9.0.96_2\\webapps\\ROOT.war'
			}
		}
	}
}
