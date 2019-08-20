node {
	stage('Git checkout') {
		git 'https://github.com/kayartaya-vinod/test-microservices'
	}	
	stage('Compile and package') {
		def mvnHome = tool name: 'maven-361', type: 'maven'
		sh "${mvnHome}/bin/mvn package"
	}
}