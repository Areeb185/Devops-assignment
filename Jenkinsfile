node{
    // stage('SCM')
    // {
    //     git branch: 'master' , url: 'https://github.com/Areeb185/Devops-assignment.git'
    // }

    // stage('build'){
    //     sh 'docker build -t form1 .'
    // }

    // stage("Nexus"){
    //     sh 'docker login -u admin -p Areeb@123 127.0.1.1:8087'
    //     sh 'docker tag form1:latest 127.0.1.1:8087/form1:latest '
    //     sh 'docker push 127.0.1.1:8087/form1:latest'
    // }
   stage('Deploying to Kubernetes') {
      
sh '/usr/local/bin/kubectl get nodes'
        
// withKubeConfig([credentialsId: 'config1']) {
//  echo "logging  in k8s success"
//  sh 'kubectl apply -f Secret.yaml'
//  sh 'kubectl apply -f Deployment.yaml'
//  sh 'kubectl get deployment'
//         }
    }
}
