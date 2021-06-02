pipeline {
    agent any
    stages{
         stage ('Testing') {
             steps{
                 sh '${WORKSPACE} /test.sh'
             //sh('test.sh')
             }
           }
       }
}
