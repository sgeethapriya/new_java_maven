node{
	stage('SCM Checkout'){
		git 'https://github.com/sgeethapriya/new_java_maven.git'
	}
	stage('Compile-Package'){
		dev mvnHome = tool name: 'Maven3', type:'maven'
		sh "${mvnHome}/bin/mvn/package"
	}
}

