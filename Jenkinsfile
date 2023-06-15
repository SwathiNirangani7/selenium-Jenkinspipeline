node {
	stage ('SCM checkout'){
		git "https://github.com/puneetbhatia77/selenium-Jenkinspipeline"
		}
	stage ('Build'){
    	dir("comtest") {
	   sh "mvn clean install"
       }
	}
}
    
