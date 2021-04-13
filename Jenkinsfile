@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
     stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
    }
}
