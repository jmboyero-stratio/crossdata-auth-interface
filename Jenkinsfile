@Library('libpipelines@master') _

hose {
    EMAIL = 'crossdata'
    MODULE = 'crossdata-auth-interface'
    DEVTIMEOUT = 20
    RELEASETIMEOUT = 20
    FOSS = true
    REPOSITORY = 'crossdata-auth-interface'
    BUILDTOOLVERSION = '3.5.0'
    NEW_VERSIONING = true
    DEPLOYONPRS = false
    SFTP_UPLOAD_SKIP = true
    DEV = { config ->
        doPackage(config)
        doDeploy(config)            
    }
}
