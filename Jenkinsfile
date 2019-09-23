pipeline {
        agent any
        stages{
                stage('Initializing...'){
                        steps{
                                sh 'echo "Starting phase one..."'
                        }
                }
                stage('Getting key...'){
                        steps{
                                sh 'echo "Getting key from 0l4bonedb..."'
			                  }
                }
                stage('Getting drones4all fake image...'){
                        steps{
				                        sh 'echo "Add missing parameter to next command to allow interaction through terminal..."'
                                sh 'docker run --rm -d --name=0l4b3nc 0l4bteam/0l4bk1t:0l4b3nc'
				                        sh 'echo "Interact with container..."'
				                        sh 'echo "Inside the container execute /0l4benc.sh to get the fake image..."'
				                        sh 'echo "Don\'t forget to stop the container at the end..."'
				                        sh 'echo "EOL..."'
			                  }
                }
        }
}
