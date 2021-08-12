# iframe-integration-demo

HTML `iframe` is used to embed another HTML document within the current one. You can integrate the treasurekey games in your dapp with just the `src` attribute. Add the following to your code base and your are good to go. Example: [Autoshark](https://autoshark.finance/coin-flip)

```html
<iframe width="100%" height="100%" frameborder="0" src="https://treasurekey.bet/coin-flip?partner=<NAME-OF-THE-APPLICATION>"></iframe>
```

## Whitelabeling

For partner integration, we have a custom whitelabeling setting. You have to send the preferred values to us. Currently we support the following parameters. 

```js
{
    name: <NAME-OF-THE-APPLICATION>,
    tokenName: <YOUR-TOKEN-NAME>,
    tokenAddress: <YOUR-TOKEN-ADDRESS>,
    logo: <LOGO>,
    link: <URL>,
    bgImage: <BACKGROUND-IMAGE>,
},
```

## Support 

Telegram: [https://t.me/treasurekeygroup]

