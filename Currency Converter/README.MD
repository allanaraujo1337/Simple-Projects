You need to get your own api keyand replace it IN index.js file on line 28 :

const response = await fetch(`https://v6.exchangerate-api.com/v6/[YOUR_KEY]]/latest/${fromCur.value}`);
