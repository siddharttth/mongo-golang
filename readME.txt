--my GO111MODULE was off by default--
go env -w GO111MODULE=on
go mod init <folder name>
go get "github.com/julienschmidt/httprouter"
go get "gopkg.in/mgo.v2"
    |_
      |go get "gopkg.in/mgo.v2/bson"