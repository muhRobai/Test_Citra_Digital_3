# Test_Citra_Digital_3

## Soal 3
 Buat webservice untuk salah satu fungsi di atas (boleh pilih nomor 0 atau nomor 1)
 
## To use the apps
1. make sure you have install golang and docker
2. `docker build -t nama_file .` to build the apps with docker
3. `docker image` to check your build docker
4. and run the docker with `docker run -it -p 8080:8080 name_file`
5. enjoy the apps


## End Point
1. `http://(default_docker_ip):8080/sort` with body input {"text"} and method {"POST"} for sort
2. `http://(default_docker_ip):8080/sum` with bodt input {"text"} and method {"POST"} for sum

## For testing unit
1. `cd Controller`
2. `cd sum || cd sort`
3. `go test -v`
 
