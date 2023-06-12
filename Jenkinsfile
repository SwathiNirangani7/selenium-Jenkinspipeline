node {
	stage ('SCM checkout'){
		git "https://github.com/SwathiNirangani7/selenium-Jenkinspipeline"
		}
	stage ('Build'){
    	dir("comtest") {
	   sh "mvn clean install"
       }
	}
}
