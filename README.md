- Prisma setup

```shell
npx prisma init
```

- スキーマ定義をDBから取得してschema.prismaとの差分を表示

```shell
npx prisma db pull --print
```

- スキーマ定義をDBから取得してschema.prismaに反映

```shell
npx prisma db pull
```


- Prismaクライアントツールを更新

```shell
npx prisma generate
```




# 参考

- <https://www.apollographql.com/docs/apollo-server/getting-started/>

# Appolo Server & GraphQL

```shell
npm init --yes && npm pkg set type="module"
```

```shell
npm install @apollo/server graphql
```

```shell
mkdir src
touch src/index.ts

npm install --save-dev typescript @types/node

touch tsconfig.json

```

- tsconfig.json編集


```shell
npm run compile && node ./dist/index.js
```

# schema.prismaからGraphQL関連自動生成

- prisma-nestjs-graphql
  <https://github.com/unlight/prisma-nestjs-graphql>
- <https://zenn.dev/mano_r/articles/8d25be4b4452dd>

```shell
npm i -D prisma-nestjs-graphql class-transformer

```
