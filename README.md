# The Cool Project

The Cool project is a really cool project. It allows to create uncollaterallized loans on top of Aave V2 for impactful project that aim to make the planet great again.
You can check the app on [Netlify](https://the-cool-project.netlify.app/).

## Web App

```bash
cd wep-app
# and
npm run dev
# or
yarn dev
```

## Truffle

To deploy contract on Kovan network
```bash
cd truffle
# and
npm run migrate:kovan
```

Then, update the addresses and abis in the `contracts` folder in `web-app`.

## TODO

Short terms:
- [] Review link in menu (maybe merge some pages).
- [] Test project proposal creation and voting.
- [] Update SC with timeframe for vote.
- [] Add a getter for mapping?
- [] Improve Form with a border.

Long terms:
- [] Implement conviction voting to vote on projects.
- [] Allow projects to run for being whitelisted.

## Utils

- DAI address: 0xff795577d9ac8bd7d90ee22b6c1703490b6512fd
- First account: 0xFE3B557E8Fb62b89F4916B721be55cEb828dBd73
- Address to whitelist: 0x627306090abaB3A6e1400e9345bC60c78a8BEf57