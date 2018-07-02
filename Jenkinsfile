node {
   stage('Preparation') {
      git 'https://github.com/jpascas2/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}
