# swag-claim-management

## Working on specification

### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and `cd`
   - Run `npm install`

### Usage

1. Run `npm start`
2. Checkout console output to see where local server is started. You can use all [links](#links) (except `preview`) by replacing git url with url from the message: `Server started <url>`
3. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
4. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
   **TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
5. Once you finish with the changes you can run tests using: `npm test`
6. Share you changes with the rest of the world by pushing to GitHub :smile:

Пример подключения в проект клиентской зависимости:

```
<dependency>
    <groupId>com.valitydev</groupId>
    <artifactId>claim-management</artifactId>
    <version>1.45-5184fdc-client</version>
</dependency>
```

Пример подключения в проект серверной зависимости:

```
<dependency>
    <groupId>com.valitydev</groupId>
    <artifactId>claim-management</artifactId>
    <version>1.45-5184fdc-server</version>
</dependency>
```

**Нельзя использовать две зависимости одновременно (из-за одинакового пути в package)**