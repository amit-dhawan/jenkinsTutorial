// Declarative pipeline syntax example

pipeline {
  agent {
          docker { image 'node:12-alpine' }
      }

    stages{


            stage("build"){

                    steps {

                        echo ' building the node project ...... !!'

                        sh 'node --version'
                      


                    } // steps ends

                } // stage ends






    } // stages end


} // pipeline ends
