pipeline {
    agent none
    environment {
        PLUGIN_NAME = "org.globalqss.idempiere.LCO.detailednames"
        PLUGIN_NAME2 = "org.globalqss.idempiere.LCO.withholdings"
        IDEMPIERE_VERSION = "12.0.0"
    }
    stages {
        stage('Compile') {
            agent {
               docker {
                    image 'carl0jgr/idempiere-source-builder:12'
                     args '--entrypoint=\'\' -u root:root -v /var/jenkins_home/.m2:/root/.m2'              
                  }
            }
            steps {
                dir('target-platform') {
                    git branch: '12.0', url: 'https://github.com/ingeint/idempiere-target-platform-plugin.git'
					sh './plugin-builder build ../${PLUGIN_NAME} ../${PLUGIN_NAME2}'
                    archiveArtifacts artifacts: "target/${PLUGIN_NAME};singleton:=true-${IDEMPIERE_VERSION}.${BUILD_NUMBER}.jar", fingerprint: true
                    archiveArtifacts artifacts: "target/${PLUGIN_NAME2};singleton:=true-${IDEMPIERE_VERSION}.${BUILD_NUMBER}.jar", fingerprint: true
                    sh 'rm -rf target ../${PLUGIN_NAME}/target ../${PLUGIN_NAME2}/target'
                }
            }
        }
    }
}
