# Dockerを使ったコンテナ開発・運用ハンズオン

本資料はDockerを使ったコンテナでの開発及びコンテナを使用した運用を一通り習得し、実際の現場で使用できるようにするための資料である。

ハンズオン実施時にはネットワークが重くなることもあるので、最低限Dockerのインストールを済ませておくのが望ましい。

LinuxユーザーであればそのままネイティブにDockerをインストールすればよいが、そうでない場合は各OSに従ってDockerを動かす機構を用意する。

# Dockerのインストール

Linux上でのインストールは省略する

## Docker Toolbox

Dockerサーバは基本的にはLinux上で動くソフトウェアなので、VirtualBoxなどでLinux VMを立ち上げ、
その上でDockerサーバを起動させるという機構がDocker machineだが、これの導入を容易にしてくれるがDocker Toolboxである。
https://docs.docker.com/toolbox/overview/

あまり推奨されてはいないが、Windowsの場合はDocker for Windows がWindowsのPro版であることをが要求するため、toolboxを使わざるをえない場合もある。
また、Docker for Macの場合はストレージ問題が残っている可能性があるので、toolboxを選択肢に入れる場合もある。

## Docker for Mac

Mac で Docker をインストールする場合は、これを使うのが楽。
Dockerのバージョンアップも自動で検出して実行してくれる
https://docs.docker.com/docker-for-mac/install/#download-docker-for-mac

## Docker for Windows

Windows でかつ Pro版を使用しているのならば、Docker for Windowsが最高の選択肢であると思われる。
Docker for Mac のようなストレージの心配もないらしい。
https://docs.docker.com/docker-for-windows/install/
