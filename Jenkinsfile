node{
 stage('SCM Checkout'){
  git 'https://github.com/yaminieluri/test_pull' 
 }
 stage('Compile-Package'){
  sh "mvn package"
 }
}
