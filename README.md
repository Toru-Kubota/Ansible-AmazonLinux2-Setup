## 内容
内容・使用方法に関しては[AmazonLinux2設定用Ansibleサンプル](https://qiita.com/tkubota/items/a7533c5dc18ec72f0521)を参照下さい。
## ディレクトリ構成

```
.
|-- inventory
|   |-- group_vars
|   |   `-- all.yml
|   `-- hosts
|-- roles
|   `-- setup
|       |-- files
|       |-- tasks
|       |   `-- main.yml
|       `-- templates
|           `-- snmpd.conf.j2
`-- site.yml
```
