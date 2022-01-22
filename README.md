# API Gobolada Soomaaliya

Waxaan sameeyay api taas oo ku soo bandhigaysa **Gobolada** dalka iyo **Degmooyinkooda** 

## side ayaad u isticmaaleysaa

Waxey ay ku xirantahay `programming language ka` aad adeegsaneyso balse halkaan waxaan kugu tusi doona **2bo** luuqadood oo kala ah `Javascript ` iyo `Python`

### 1. javascript

Si aad u soo aqriso gobolada Qor code kaan 

```javascript
const api_url = 'https://gobolada-soomaaliya.herokuapp.com/gobolada';
async function sooAqriGobolada(url) {
  const response = await fetch(url);
  const data = await response.json();
  console.log(data);
}
sooAqriGobolada(api_url);
```

### 2. python

Si aad u aqriso gobolada adiga oo isticmaalaya `python`  qor code kaan

```python
import requests
import json 
res = requests.get('https://gobolada-soomaaliya.herokuapp.com/gobolada')
response = json.loads(res.text)
print(response)
```

## Sidee ayaad wax ugu soo dari kartaa api daan?

Marka hore waxaa loo baahanyahay inaad soo `degsato` **git** kadibna qor **command**gaan 

```git
git clone https://github.com/AbdirahimAhmedNor/API-gobolada-Soomaaliya.git
```

kadibna waxaad qortaa 

```git
npm install
```

kadib waxaa terminalka kusii qortaa

```git
npm start
```

Intaas kadib barrowsarka fur waxaad qortaa 

```git
http://localhost:3000/gobolada
```


