# Fast Ruby Install

brewを用いて最新バージョンのrbenv, ruby-buildと、指定したバージョンのruby, rubygems, bundlerをインストールするスクリプトです。  

## Installation

`RUBY=2.7.3` `GEM=3.2.28` `BUNDLERS=(2.2.28)` にインストールしたいソフトウェアバージョンを指定して、ターミナルで実行して下さい。

※ bundlerを複数インストールしたい場合は `BUNDLERS=(1.17.3 2.2.28)` の様にします。

**Run Example**

```
/usr/bin/env bash -c "RUBY=2.7.3 GEM=3.2.28 BUNDLERS=(2.2.28) $(curl -fsSL https://raw.githubusercontent.com/Tea-and-Coffee/fast-ruby-install/master/install.sh)"
```

## Other Usage

スクリプトファイルを編集して実行したい場合のために、run.shを用意しています。

run.shを開き、RUBY, GEM, BUNDLERSのバージョンナンバーを書き換えます。  

※ bundlerを複数インストールしたい場合は BUNDLERS=(1.17.3 2.2.28) の様にします。  

**Edit run.bash**

```ruby
# ruby 2.7.3の環境
RUBY=2.7.3
GEM=3.2.28
BUNDLERS=(2.2.28)
```

書き換えたらスクリプトを実行します。

**Run script**

```bash
$ bash run.sh
```
