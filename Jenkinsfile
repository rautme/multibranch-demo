@Library('github.com/rahulmr/multibranch-demo-lib') _
standardBuild {
    environment = 'golang:1.8.1'
    mainScript = '''
go version
go build -v hello-world.go
'''
    postScript = '''
ls -l
./hello-world
'''
}
