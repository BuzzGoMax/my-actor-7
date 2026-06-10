[My Actor 7](https://apify.com/signaliz/my-actor-7?fpr=data)

## Convert OpenAI Image 1 Model Base 64 to useable URL

## Included features

- **[Apify SDK](https://docs.apify.com/sdk/js/)** - toolkit for building [Actors](https://apify.com/actors)
- **[Input schema](https://docs.apify.com/platform/actors/development/input-schema)** - define and easily validate a schema for your Actor's input
- **[Dataset](https://docs.apify.com/sdk/js/docs/guides/result-storage#dataset)** - store structured data where each object stored has the same attributes
- **[Axios client](https://axios-http.com/docs/intro)** - promise-based HTTP Client for Node.js and the browser
- **[Cheerio](https://cheerio.js.org/)** - library for parsing and manipulating HTML and XML

## Pull the Actor for local development

If you would like to develop locally, you can pull the existing Actor from Apify console using Apify CLI:

1. Install `apify-cli`

**Using Homebrew**

```
$brew install apify-cli
```

**Using NPM**

```
$npm -g install apify-cli
```
2. Pull the Actor by its unique `<ActorId>`, which is one of the following:

- unique name of the Actor to pull (e.g. "apify/hello-world")
- or ID of the Actor to pull (e.g. "E2jjCZBezvAZnX8Rb")

You can find both by clicking on the Actor title at the top of the page, which will open a modal containing both Actor unique name and Actor ID.

This command will copy the Actor into the current directory on your local machine.

```
$apify pull <ActorId>
```

## Documentation reference

To learn more about Apify and Actors, take a look at the following resources:

- [Apify SDK for JavaScript documentation](https://docs.apify.com/sdk/js)
- [Apify SDK for Python documentation](https://docs.apify.com/sdk/python)
- [Apify Platform documentation](https://docs.apify.com/platform)
- [Join our developer community on Discord](https://discord.com/invite/jyEM2PRvMU)