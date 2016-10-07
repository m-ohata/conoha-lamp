# conoha-lamp

## Overview (概要)

Vagrant + ConoHa(VPS) + Ansible を組み合わせた
開発環境の学習用プロジェクトです。

## Usage (使い方)

```Bash
$ cp -R default test-lamp

$ cd test-lamp

$ vim test-lamp
// 下記の内容を書き換えてください。
    # api token
    conoha.username           = "gncu****"
    conoha.password           = "********"
    conoha.tenant_name        = "gnct****"

$ vagrant up
```

ansible_localのインストールに失敗するケースがありますが、  
Ansible自体のインストールは完了しているので、  
再度`vagrant provision`コマンドを実行してください。

