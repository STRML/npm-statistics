# npm-statistics

![NPM Stats](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSTRML%2Fnpm-statistics%2Fmaster%2Fstats.json)

NPM Download Statistics for STRML Open Source Projects. Updated Daily.

## Downloads

<!-- Please do not modify this auto generated content -->
<!-- AUTO-GENERATED-CONTENT:START (PACKAGES) -->
| Name                                                 | Downloads                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [message](https://www.npmjs.com/package/message)     | jOOQ; SQL [insert into "public"."download_count" ("package_name", "date", "count") values (?, cast(? as date), ?)]; ERROR: could not access status of transaction 0
  Detail: Could not write to file "pg_subtrans/3DF8" at offset 81920: No space left on device.; nested exception is org.postgresql.util.PSQLException: ERROR: could not access status of transaction 0
  Detail: Could not write to file "pg_subtrans/3DF8" at offset 81920: No space left on device.                                                                                    |
| [error](https://www.npmjs.com/package/error)         | Internal Server Error                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [timestamp](https://www.npmjs.com/package/timestamp) | 2022-05-05T00:22:20.360+0000                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [path](https://www.npmjs.com/package/path)           | /npm-stat/api/download-counts                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Sum**                                              | **jOOQ; SQL [insert into "public"."download_count" ("package_name", "date", "count") values (?, cast(? as date), ?)]; ERROR: could not access status of transaction 0
  Detail: Could not write to file "pg_subtrans/3DF8" at offset 81920: No space left on device.; nested exception is org.postgresql.util.PSQLException: ERROR: could not access status of transaction 0
  Detail: Could not write to file "pg_subtrans/3DF8" at offset 81920: No space left on device.Internal Server Error/npm-stat/api/download-counts02022-05-05T00:22:20.360+0000** |
<!-- AUTO-GENERATED-CONTENT:END -->

### Wanna use `npm-statistics`?

1. `Fork` this repository.
2. Add your npm username/author or list of packages in `package.json` as `npm-stats` key.
   for author

```js
{
  "npm-stats": "STRML"
}
```

or for packages

```js
{
  "npm-stats": [
    "markdown-magic",
    "analytics"
  ]
}
```

3. Run `npm i` and then `npm start` to generate the Downloads.
4. The repo comes with a daily CRON job that updates the Downloads.
5. For updating the badge replace `DavidWells` in badge endpoint to your github username/orgname.
   https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F`username`%2Fnpm-statistics%2Fmaster%2Fstats.json
6. Enable `GitHub Actions` for your forked repo, as it is enabled by default for forks.

## Ref

- [npmtotal](https://github.com/maddhruv/npmtotal) - Find you npm download statistics
- [Props to ClearTax for this awesome action](https://github.com/ClearTax/npm-statistics)
