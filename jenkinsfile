pipeline {
    agent any

    stages {
        stage('--------拉取git仓库代码--------') {
            steps {
                echo '拉取git仓库代码 success'
            }
        }
         stage('--------maven构建中--------') {
            steps {
                echo 'maven构建成功 success'
            }
        }
         stage('--------docker自定义镜像--------') {
            steps {
                echo 'docker自定义镜像 success'
            }
        }
        stage('--------推送aliyun仓库--------') {
            steps {
                echo '推送aliyun仓库 success'
            }
        }
        stage('--------通知目服务器拉取镜像中--------') {
            steps {
                echo '通知目服务器拉取镜像中 success'
            }
        }
    }
}
