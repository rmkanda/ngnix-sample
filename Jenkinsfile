node () {
    sh 'ls -al'
    // sh 'docker build . -t ngnix-sample:v1'
    sh 'echo "APP_VERSION=v2" > build.properties'
    // sh 'env >> build.properties'
    archiveArtifacts 'build.properties'
}
