@Library('jenkins-shared-library') _

def configMap = [
    PROJECT: "roboshop",
    COMPONENT: "user"
]

if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ) { // if not equal to main
    nodejsEKSPipeline(configMap)  // by default it will call, call fuction iside this pipeline
}

else {
    echo "Please proceed with PROD process"
}