# WXT template

## Features

- 完全な WXT の開発環境
- Biome と Lefthook による Git Hook ベースの Linter / Formatter
- commitlint と Conventional Commits によるバージョニング
- Chrome Web Store と Add-ons for Firefox への自動公開

## Usage

- [このリポジトリから、新しいリポジトリを作成](https://github.com/new?template_name=wxt-template&template_owner=simochee)
- [リポジトリにシークレットを登録](#repository-secrets)
- GitHub Actions ワークフローや `package.json`、 `wxt.config.ts` などに拡張機能の情報を入力
- 開発開始！

## Repositry Variables

Chrome Web Store と Add-ons for Firefox から取得できる拡張機能の ID を設定します。

- `CHROME_EXTENTION_ID`
- `FIREFOX_EXTENTION_ID`

## Repository Secrets

[`wxt submit init`](https://wxt.dev/api/cli/wxt-submit-init.html) で作成される `.env.submit` を元に、次の値を設定してください。

### Chrome Web Store

- `CHROME_CLIENT_ID`
- `CHROME_CLIENT_SECRET`
- `CHROME_REFRESH_TOKEN`

### Add-ons for Firefox

- `FIREFOX_JWT_ISSUER`
- `FIREFOX_JWT_SECRET`

## License

MIT
