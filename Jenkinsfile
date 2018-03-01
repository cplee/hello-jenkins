node {
  stage('Build') {
    def commitHash = checkout(scm).GIT_COMMIT

    echo "Building #{commitHash}"
  }

  stage('Deploy') {
    echo "Deploygin #{commitHash}"
  }

}
