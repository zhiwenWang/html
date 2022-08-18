node{
  def mvnHome
  stage('拉取代码'){
      checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/zhiwenWang/html.git']]])  }
}
