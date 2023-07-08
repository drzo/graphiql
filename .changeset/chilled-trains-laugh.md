---
'codemirror-graphql': major
'graphql-language-service': major
'graphql-language-service-cli': major
'graphql-language-service-server': major
'monaco-graphql': major
'cm6-graphql': minor
'@graphiql/react': minor
'@graphiql/toolkit': minor
---

_BREAKING CHANGE:_ drop commonjs exports in all libraries except for `graphiql` and `@graphiql/react`

all previously `<package>/esm` paths are now `<package>/dist`
for example, `monaco-graphql/esm/initializeMode` is now `monaco-graphql/dist/initializeMode`