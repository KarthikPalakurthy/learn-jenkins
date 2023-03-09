pipeline {
    agent {
        label 'ansible'
        }
 stages {

        steps('Hello') {
           step {
               echo 'Hello World!'
           }

        steps('Hello1') {
            step {
                echo 'Hello World!, This is a test message'
            }

        steps('Hello2') {
              step {
                 echo 'Thank you'
              }
            }
        }

 }
}
}