pipeline{
  agent any
  tools{
    maven 'MAVEN_HOME'
  }
  stages{
    stage('Git Checkout Stage'){
      steps{
        echo " Cloning project from git"
        git branch: 'master',url:'https://github.com/adityam31031998/banking-finance.git'
      }
    }
    stage('Package Stage'){
      steps{
        echo "Create a package "
        git branch: 'master',url:'https://github.com/adityam31031998/banking-finance.git'
      }
    }
  }
}
