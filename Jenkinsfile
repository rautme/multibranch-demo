@Library('github.com/cloudbeers/multibranch-demo-lib@alt') _
standardBuild {
    environment = 'golang:1.8.1-alpine'
    mainScript = '''
go version
go build -v hello-world.go
'''
    postScript = '''
ls -l
./hello-world
'''
}
