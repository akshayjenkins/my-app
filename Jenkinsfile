
node {
   
   stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/akshayjenkins/my-app'
   }
   stage('Compile Package'){
	   // Build using maven
	 sh 'mvn package'
   }
}
   
  

