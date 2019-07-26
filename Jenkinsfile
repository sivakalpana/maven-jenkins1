node {
   stage('SCM Checkout'){
      git 'https://github.com/sivakalpana/maven-jenkins1'
      }
    stage('compile package'){
       //get maven homepath
      
       sh "${mvnHOME}/bin/mvn package"
      }
}      
