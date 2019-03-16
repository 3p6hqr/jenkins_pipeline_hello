node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
stage('QA Approval'){
        input "QC Pass?"        
}
node {
    stage('up to production env'){
        echo "Production pass"
    }
}
