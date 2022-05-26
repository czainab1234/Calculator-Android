stage(‘Get Source’) {
checkout([$class: ‘GitSCM’, 
branches: [[name: ‘*/’ + main]],           
doGenerateSubmodule Configurations: false, 
extensions: [[$class: ‘RelativeTargetDirectory’,     
relativeTargetDir:Calculator-Android],
[$class: ‘CloneOption’, timeout: 20]], 
submoduleCfg: [], 
userRemoteConfigs: [[url: ‘https://github.com/Rakesh8007/Calculator-Android.git’ ]]])
}
