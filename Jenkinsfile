pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                chmod +x ./helloworld.sh
		echo "$PATH"
		sh ./helloworld.sh
            }
        }
    }
}
