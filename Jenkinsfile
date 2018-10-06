node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/jglick/simple-maven-project-with-tests.git'
      git 'https://github.com/botla207/gitbox.git'
   }
   stage('Build') {
      bat '''
      echo "Building....."
      call "C:/Ashok/Build.bat" stop
      EXIT /B 0 
      '''
      }
   stage('Results') {
      echo "Unites
      build job:'Build'
     
   }
}
