properties([pipelineTriggers([githubPush()])])
node {
   stage('git'){
    git credentialsId: '502a475a-5798-4617-9367-1f84208c9ce0', url: 'git@github.com:tsv1982/hello-html.git'
   } 
   stage('git2'){
     sh 'ls -la'
   } 
}
