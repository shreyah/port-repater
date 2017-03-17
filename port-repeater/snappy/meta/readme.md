Template for a snappy project in Go. To build ...

1. edit main.go to have the desired functionality
2. add the necessary capability to meta/package.yaml
3. edit the files in meta (including this one) to reflect your project

= build for each arch =
2. $cd /bin/x86_64-linux-gnu
3. $go build ../../
4. $cd ../arm-linux-gnueabihf
5. $go build ../../

= make the snap =
6. $cd ../../
7. snappy build

= test the snap =
