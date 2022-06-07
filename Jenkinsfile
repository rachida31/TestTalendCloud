node {
    stage('Clone') {
        git branch: 'main', credentialsId: 'cb7123bb-6806-4c3c-b603-cd1264f868f7', url: 'https://github.com/rachida31/TestTalendCloud.git'
}
    stage('Build') {
        bat '''cd TestTalendCloud
                javac Main.java'''
}
    stage('Run') {
        bat '''cd TestTalendCloud
                java Main'''
        
    }
}