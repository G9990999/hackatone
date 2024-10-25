# Ports and endpoints

import requests

url = 'http://62.113.108.20:8081'

print(requests.get(url+'/profile?point=Vanessa Lynn').json())
print(requests.get(url+'/get_role?point=Vanessa Lynn').json())
print(requests.get(url+'/get_stash?point=Vanessa Lynn').json())

#print(requests.get(url+'/upload_nft?point=Vanessa Lynn&nft=rasfsasdopiqwer').json())

print(requests.get(url+'/get_nft?point=Vanessa Lynn').json())



## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```
