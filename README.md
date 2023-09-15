# actions-runner

> A GitHub App built with [Probot](https://github.com/probot/probot) that actions-runner lets you run github workflows on ibm ppc64le and s390x architectures.

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t actions-runner .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> actions-runner
```

## Contributing

If you have suggestions for how actions-runner could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2023 Adilhusain Shaikh
