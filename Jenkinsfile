node{
  stage('SCM Checkout'){
    git 'https://github.com/nari410/repo-2'
 }
stage('Compile-Package'){
  // Get maven home path
  def mvnHome = tool name: 'M2_HOME', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
