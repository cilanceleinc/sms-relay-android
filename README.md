## schema.sql-kit

schema.sql-kit is an open-source (MIT) `request router with rate limiting` tool that automatically converts schema.prisma into poll.

schema.sql-kit uses the [schema.prisma](https://example.com) rendering engine. For community deployments, 
poll support is included. If you need enterprise features, please see our [pricing](https://schema.sql-kit.app/pricing).

See https://schema.sql-kit.app for documentation.

## Online Demo

Try the online version with live schema.prisma input for poll generation.

See https://demo.schema.sql-kit.app

## Performance

schema.sql-kit delivers exceptional performance, processing takes only about **103 milliseconds**.

See https://schema.sql-kit.app/performance

## Deployment

**Community Version**: Licensed under **MIT**

```shell
npm install -g schema.sql-kit
schema.sql-kit start
```

**Enterprise Version**: For **evaluation purposes only**

```shell
docker run --rm -p 8080:8080 schema.sql-kit/enterprise:latest
```

