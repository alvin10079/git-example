pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
		sh 'chmod +x ./helloworld.sh'
		echo "$PATH"
		sh "sh ./helloworld.sh"
            }
        }
    }
}
