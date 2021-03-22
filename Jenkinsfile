node {
    stage('commit') {
    
                    
      git 'https://github.com/Indhuja-R/javac.git'

     
    }
    stage('build') {
       
       
       def mvnHome=tool name: 'maven', type: 'maven'
       sh "${ mvnHome}/bin/mvn clean"
    
      
    }
   
    
  
}
