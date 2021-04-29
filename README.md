# Usage
```
docker build . -t beholder/image-name

docker run -it -p 3000:3000 -e "REACT_APP_INFURA_ID=infuraID" -e "REACT_APP_PORTIS_ID=portisID" -e "REACT_APP_RPC_CONFIGS=1|https://mainnet.infura.io/v3/infuraID" -e "REACT_APP_FORTMATIC_KEY=fortmaticKey" beholder/image-name yarn start
```

Dev server should be up and running after a short while, and the app should be available on `http://localhost:3000`.
