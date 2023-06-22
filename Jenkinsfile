node{
    stage('SCM')
    {
        git branch: 'master' , url: 'https://github.com/Areeb185/Devops-assignment.git'
    }

    stage('build'){
        sh 'docker build -t form1 .'
    }

    stage("Nexus"){
        sh 'docker login -u admin -p Areeb@123 172.31.138.178:8087'
    }
}
