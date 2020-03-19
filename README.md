# SCFAutoPAC

## usage

`http://endpoint?PROXY=SOCKS5_127.0.0.1:1080`

`http://endpoint?PROXY=HTTPS_127.0.0.1:1080`

`http://endpoint?PROXY=HTTP_127.0.0.1:1080`

## dirty hack

There's a dirty hack of scf-go-lib/cloudfunction in [cloudfunction](github.com/yzs981130/scf-go-lib/cloudfunction) to satisfy my needs.

- remove HTML escape in `json.Marshal`

- remove the leading and trailing quotes

## example

GET `https://service-ajg9rwsh-1252057789.bj.apigw.tencentcs.com/release/pac?PROXY=SOCKS5_172.17.1.86:1080`