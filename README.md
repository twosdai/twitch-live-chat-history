# twitch-live-chat-history

This small node.js application `twitch-live-chat-history`, allows you to store chat history of a Twitch live stream.

## Getting Started

### Prerequisites

You need to install `node.js` ([see here](https://nodejs.org/en/))

### Install

After cloning the project, you need to install npm packages in the project.

If you have at least node.js 10+, do:
```
npm ci
```
or if you are under node 10, use:
```
npm i

OR 

npm install
```

### Run The APP!

Replace `TWITCH_CHANNEL_NAME` by the the name of the Twitch channel you want to store the history.

```
npm start TWITCH_CHANNEL_NAME
```

You can listen from multiples Twitch channels, just add it as arguments:

```
npm start TWITCH_CHANNEL_NAME_1 TWITCH_CHANNEL_NAME_2 TWITCH_CHANNEL_NAME_3
```

## How it works?

When application is running, it will display all the chats.

If you want to retrieve chats, it has been stores in a Database called `chats.db`.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors 🌈

- Samyak Bambole - Initial work - [samyakbambole](https://github.com/samyakbambole)
- Joël Piazzalunga-Lerat - [jpiazzal](https://github.com/jpiazzal)
- Nicholas - [nicolashacala](https://github.com/nicolashacala)
- Talha - [symtalha14](https://github.com/symtalha14)
- Erdem Uslu [erdemuslu](https://github.com/erdemuslu)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Make Sure to Give This Repository a Star! ⭐

## I would Like to thank all of the Contributors that helped building this project. Without Them, This won't be possible. 😀🌈
