pipeline{
  agent any
  tool{
    maven 'MAVEN_HOME'
  }
  stages{
 stage('Git Checkout'){
   steps{
     echo " Cloning project from git"
     git branch: 'master',url:'https://github.com/adityam31031998/banking-finance.git'
   }
 }
  }
}
