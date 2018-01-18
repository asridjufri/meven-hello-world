node('dockernya asri') {
          checkout scm
          stage('build') {
              withMaven(jdk: 'Default Java', maven: 'Default Maven') {
                dir('my-app') {
                  sh 'mvn clean install'
                }

              }
          } 
        }
