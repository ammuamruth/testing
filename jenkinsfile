pipeline {
	agent {
		dockerfile true
	}
	stages {
		stage('example'){
			steps {
				echo 'hello world'
				sh 'echo myCustomEnvVar = $myCustomEnvVar'
			}
		}
	}
}
