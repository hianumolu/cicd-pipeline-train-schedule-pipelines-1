pipeline {
 agent any 
 stages {
  stage{'Build') {
   steps {
    echo 'Running build automation'
    sh './gradlew build --nodaemon'
    archiveartifacts artifacts 'dist/trainSchedule'
        }
        
       } 
   }
}
