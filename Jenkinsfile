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
    tools { nodejs "node" }
        stages { 
            stage ('Build') { 
                steps { 
                    sh "npm install"
                    echo "Running build phase. " 
                }
            }
            stage ('Deploy') { 
                steps { 
                    sh "npm start"
                    echo "Running deploy phase. " 
                    sh "npm stop. "
                }
            }
        }
    }
