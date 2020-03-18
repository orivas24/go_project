pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''			 
			echo "BUILD"
			echo "$HOME"
			cd final_final_master/src/
			go install ./api/api.go ./api/convert.go
			cat $HOME/bin/ 
		
'''
            }
        }
        stage('Two') {
            steps {
                sh ' echo "Step Two" '
            }
        }
        stage('Three') {
            steps {
                sh ' echo "Step Three" '
            }
        }
    }
}
 
