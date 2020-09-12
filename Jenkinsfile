// Declarative pipeline syntax example

pipeline {
    agent any

    stages{


            stage("build"){

                    steps {

                        echo ' building the node project ...... !!'

                        nodejs('Node-12.18'){
                        sh 'node --version'
                        sh 'npm install'
                        }

                    } // steps ends

                } // stage ends

               
    } // stages end


} // pipeline ends
