dockerBuild {
    environment = 'golang:1.5.0'
    mainScript = '''
go version
go build -v sum.go
'''
    postScript = '''
ls -l
./sum
'''
}
