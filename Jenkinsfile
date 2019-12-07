  node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
    
     bat "\"${tool 'maven-3'}\" mvn clean package"  
   }
  
}


