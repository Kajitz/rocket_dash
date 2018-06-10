# README

## Project initiation

- Ruby version

` .ruby-version ` を確認してください。
もしローカルとバージョンが異なる場合は、以下のコマンドでバージョンを合わせてください。

```bash
# macOS
$ brew upgrade ruby-build
$ rbenv install | cat .ruby-version
```

- リポジトリのクローン

```bash
$ git git@github.com:kajitz/rocket_dash.git
```

- セットアップ

```bash
$ bin/setup
```

- Seedデータ

```bash
$ bundle exec rake db:seed_fu
```

## Memo

` $ find config/ -name '*.*' | xargs sed -i "" 's/rocket_dash/project_name/g' `
` $ find config/ -name '*.*' | xargs sed -i "" 's/RocketDash/project_name/g' `
