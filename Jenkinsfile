node{
 stage('SCM checkout'){
   git 'http://localhost:8080/job/git-maven-pip'
 }
stage('compile-package'){
 sh 'mvn package'
}
}
