node {
	slackSend "Build Started - ${env.JOB_NAME} ${env.BUILD_NUMBER} (<${env.BUILD_URL}|Open>)" 
	stage('Salesforce Release build'){
		echo "Release Building..."
	}
	stage('Salesforce Release deploy'){
		echo "Release Deploy..."
	}
}