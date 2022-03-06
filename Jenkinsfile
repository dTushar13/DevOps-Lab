// pipeline {
//     agent any
//     tools { nodejs "node" }
//     stages {
//         stage('Build') {
//             steps {
//                 sh "npm install"
//             }
//         }
//         stage('Deploy') {
//             steps {
//                 sh "npm start"
//             }
//         }
//     }
// }

pipeline { 
    agent any 
        stages { 
            stage ('Build') { 
                steps { 
                    echo "Running build phase. " 
                }
            }
            stage ('Deploy') { 
                steps { 
                    echo "Running deploy phase. " 
                }
            }
        }
    }
