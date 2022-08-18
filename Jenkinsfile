node{
  def mvnHome
  stage('拉取代码'){
   		checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '2524582f-70ea-4384-a607-06e4c82a971f', url: 'https://github.com/zhiwenWang/html.git']]])
  }
}
