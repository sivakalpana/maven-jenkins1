node {
   stage('SCM Checkout'){
      git 'https://github.com/sivakalpana/maven-jenkins1'
      }
    stage('compile package'){
       //get maven homepath
      def mvnHOME = tool name: 'maven-3.6', type: 'maven'
       sh "${mvnHOME}/bin/mvn package"
      }
}      
