pipeline{
      agent any
      environment{
      VERSION='1.1.1'
      }
      stages{
            stage("build"){
            steps{
                  echo 'Hello building'
                  echo "Version number is ${VERSION}"
                  }
              }
            stage("test"){
            steps{
                  echo 'Hello testing'
                  }
            }
            stage("Deploy"){
            steps{
                  echo 'Hello deploying'
                  }
              }
      }
}
