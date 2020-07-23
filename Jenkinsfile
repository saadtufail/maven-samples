node {
  stage('SCM Checkout'){
    git 'https://github.com/saadtufail/maven-samples'
  }
  stage('Compile-Package') {
  mvn clean install
  echo 'Jenkins build for Maven Project.'
  }
  }
