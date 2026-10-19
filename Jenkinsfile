pipeline {
	agent{
		label{
			label 'built-in'
			customWorkspace '/mnt/slave-1'
		}
	}
	stages{
		stage('clean') {
			steps {
				echo "clean"
			}
		}
		stage('build') {
			steps {
				echo "build"
			}
		}
		stage('deploy') {
			steps {
				echo "deploy"
			}
		}
	}

}
