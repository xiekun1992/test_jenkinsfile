pipeline {
	agent any

	stages {
		stage('build') {
			steps {
				parallel (
					a: {
						echo 'building0...'
					},
					b: {
						echo 'building1...'
					}
				)
				
			}
		}
		stage('test') {
			steps {
				echo 'testing...'
			}
		}
		stage('deploy') {
			steps {
				echo 'deploying...'
			}
		}
	}
}
