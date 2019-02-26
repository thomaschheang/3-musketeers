# cash

La conversion entre les devises, est l'objectif du fichier cash.js
Pour obtenir les taux de conversion de chaque devise, le fichier utilise constants.js (utilisant une API), et pour avoir plus d'informations sur le nom de la devise, il utilise currencies.json.

## To Install 

```
$ npm install i
```

## How do you use it?

- In the cash/bin file, write down the following elements to modify something:
		$ node index <amount> <from> <to>
		$ node index <options>

- In the constant.js file, you can also add more currencies values to the DEFAULT_TO_CURRENCIES variable

## Examples

		$ node index.js 
		$ node index.js 10 usd eur pln
		$ node index.js --set usd aud
		& node index.js save usd aud