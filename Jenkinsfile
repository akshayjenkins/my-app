
node {
   
   stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/akshayjenkins/my-app'
   }
   stage('Compile Package'){
	   // Build using maven
     def mvnHome = tool name: 'maven', type: 'maven'
	 
	   sh "${mvnHome}/bin/mvn package"
   }
}
   
  

