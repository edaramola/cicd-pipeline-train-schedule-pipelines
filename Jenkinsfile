pipeline {
  agent any
     stages {'Build'}
         steps (
             echo "Running build automation"
             sh './gradlew build' --no-daemon //turns of the gradle daemon, speeds things up
             archiveactifacts artifacts 'dist/trainschedule.zip'
          }
        }
     }
 }
