node {
    stage ('Check SCM ') {
        git 'https://github.com/Kirthi92/eficens.git'
       }
stage ('Build Maven'){
        sh '''export M2_HOME=/home/ec2-user/apache-maven-3.6.3
        export PATH=$M2_HOME/bin:$PATH
        /home/ec2-user/apache-maven-3.6.3/bin/mvn clean package
        mvn clean package'''
    }

}
