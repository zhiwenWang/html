node{
  def mvnHome
  stage('测试'){
   		checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '2524582f-70ea-4384-a607-06e4c82a971f', url: 'https://gitee.com/lingjian1027/test-cloud.git']]])
  }
}
