node {
    def BUILD_USER = null
    
    wrap([$class: 'BuildUser']) {
        BUILD_USER = env.BUILD_USER
    }

    stage('Checkout'){        
        echo BUILD_USER
    }
}