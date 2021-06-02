pipeline {
    agent any
    stages{
         stage ('Testing') {
             steps{
                 //sh '${WORKSPACE} ./test.sh'
             sh ('chmod 777 test.sh')
             sh('./test.sh')
             }
           }
       }
}
