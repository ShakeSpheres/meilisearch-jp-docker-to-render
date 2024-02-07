# meilisearch-docker-render

Meilisearch を render.com にデプロイする

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


## Environment Variables

- `MEILI_HTTP_ADDR` -- Meilisearch サーバーを実行するアドレス (Default = `0.0.0.0:80`)
- `MEILI_MASTER_KEY` -- マスターキー (Default = `{randomly_generated_key}`)
- `MEILI_DB_PATH` -- データを永続化する場所。render.yamlにもあるので、おそらくこれを変更する必要はありません (Default = `/meili-data`)
- `MEILI_ENV` -- 環境 (Default = `development`, Option `development` `production`)

設定できるオプションの一覧 [一覧](https://docs.meilisearch.com/reference/features/configuration.html#options)
