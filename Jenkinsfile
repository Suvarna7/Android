//MAKING A CHANGE TO TEST//v2//v3
node
    {
        try {
            stage("build.clone")
            {
                checkout scm
            }
            stage("build.clean")
            {
                sh "./gradlew clean"
            }
            stage("build.package")
            {
                sh "./gradlew assembleDebug"
            }
        } catch (error) {
            throw error
        }
    }
