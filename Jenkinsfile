node{
   stage('SCM Checkout'){
       git 'https://github.com/nazariiparasiuk/nazariiparasiuk.github.io'
   }
   stage('Compile-Package'){
      def mvnHome = tool name: 'Maven', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
   }
