node{
 stage('SCM Checkout'){
  git 'https://github.com/yaminieluri/test_pull' 
 }
 stage('Compile-Package'){
  def mvnhome= tool name: 'maven', type: 'maven'
  sh "${mvnhome}\bin\mvn package"
 }
}
