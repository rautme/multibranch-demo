@Library('github.com/cloudbeers/multibranch-demo-lib') _
standardBuild {
    environment = 'golang:1.8.1-alpine'
    mainScript = '''
go version
go build -v hello-world.go
'''
    postScript = '''
echo 'Testing...'
./hello-world
'''
}
