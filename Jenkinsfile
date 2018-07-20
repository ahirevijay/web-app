node{
   stage('SCM Checkout'){
     git 'https://github.com/ahirevijay/web-app.git'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
}
