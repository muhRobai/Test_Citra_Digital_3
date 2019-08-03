# Test_Citra_Digital_2

## Soal 2
 Buat webservice untuk salah satu fungsi di atas (boleh pilih nomor 0 atau nomor 1)
 
## To use the apps
1. make sure you have install golang
2. $GOPATH/src/ clone the apps `git clone url`
3. `cd Route`
4. `go run Route.go`

## End Point
1. `localhost:8080/sort` with body input {"text"} and method {"POST"} for sort
2. `localhost:8080/sum` with bodt input {"text"} and method {"POST"} for sum

## For testing unit
1. `cd sum || cd sort`
2. `go test -v`
 
