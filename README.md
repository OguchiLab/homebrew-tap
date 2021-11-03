# OguchiLab Tap

自律分散型信号システムの通信のために、バージョンを固定した rabbitmqを独自ビルド

## インストールする前に

通常バージョンのrabbitmqをアンインストール

`brew uninstall rabbitmq`

その際に、設定ファイルが残る可能性があるので、 /PREFIX/etc/rabbitmq/ 以下のファイルはそのまま残すかバックアップしておく。

## How do I install these formulae?

`brew install oguchilab/tap/rabbitmq-stable`

Or `brew tap oguchilab/tap` and then `brew install rabbitmq-stable`.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
