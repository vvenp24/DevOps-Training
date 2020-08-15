node {

stage 'git checkout'
git 'https://github.com/dkAug01/DevOps-Training.git'

stage 'compile'
sh 'mvn compile'

stage 'test'
sh 'mvn test'

stage 'package'
sh 'mvn package'

stage 'artifacts'
archiveArtifacts 'target/*.war'


}
