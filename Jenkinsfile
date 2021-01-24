node {
    
     stage('git clone') {
     git 'https://github.com/mahipal0987/repo99.git'
   }
   stage('clean') {
      sh 'mvn clean'
   }
   stage('validate') {
      sh 'mvn validate'
   }
   stage('compile') {
      sh 'mvn compile'
   }
   stage('package') {
      sh 'mvn package'
   }
   stage('deploy') {
      sh 'mvn deploy'
   }
   }
