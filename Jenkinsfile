pipeline {
      agent any 
             stages {
                stage('Build Assets') {
                 agent any 
             steps {
                echo 'Building Assets...'
                   }
                     }
//           }
      
//          stage('Preparation') { 
//             git url: 'https://github.com/Rakesh8007/Calculator-Android.git'
//         }
      
//         stage('Dependencies') {
//                 steps(
                 
//                 sh 'sudo npm install -g react-native-cli'
//                 sh 'npm install'
//                 sh 'react-native link'
//                 sh 'export JAVA_HOME=/opt/jdk1.8.0_201'
//                 sh 'export JRE_HOME=/opt/jdk1.8.0_201/jre'
//                 sh 'export ANDROID_HOME=/android-sdk'
//                 sh 'export PATH=$PATH:/opt/jdk1.8.0_201/bin:/opt/jdk1.8.0_201/jre/bin'
//                 sh 'echo $JAVA_HOME'
//                     )
//         }
        
        stage('Clean Build') {
            steps(
                dir("android-sdk") {
                    sh "pwd"
                    sh 'ls -al'
                    sh './gradlew clean'
                     } 
                )
        }
             }
}
        
//         stage('Build release ') {
//             parameters {
//                 credentials credentialType: 'org.jenkinsci.plugins.plaincredentials.impl.FileCredentialsImpl', defaultValue: '5d34f6f7-b641-4785-frd5-c93b67e71b6b', description: '', name: 'keystore', required: true
//             }
//             dir("android") {
//                 sh './gradlew assembleRelease'
//             }
//         }
      
//         stage('Compile') {
//             archiveArtifacts artifacts: '**/*.abb', fingerprint: true, onlyIfSuccessful: true            
//         }
//     }
  
// } catch (caughtError) { 
    
//     err = caughtError
//     currentBuild.result = "FAILURE"

// } finally {
    
//     if(currentBuild.result == "FAILURE"){
//               sh "echo 'Build FAILURE'"
//     }else{
//          sh "echo 'Build SUCCESSFUL'"
//     }
   
// }

// pipeline {
//     agent any 

//     stages {
//         stage('Build Assets') {
//             agent any 
//             steps {
//                 echo 'Building Assets...'
//             }
//         }
//         stage('Test') {
//             agent any
//             steps {
//                 echo 'Testing stuff...'
//             }
//         }
//     }
// }
