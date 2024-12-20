# CLOSE TO YOU

### Biblioteca para Icons.
documentação do tabler.io
> https://tabler.io/icons
```
npm install @tabler/icons-react-native
```
### Como os itens é em SVG para conseguir renderizar.
```
npx expo install react-native-svg
```

### Biblioteca para consumir o Backend.
documentação do axios
> https://axios-http.com/docs/intro
```
npm i axios
```

### Biblioteca para pages buttons.
documentação do axios
> https://gorhom.dev/react-native-bottom-sheet/
```
npm i @gorhom/bottom-sheet@^5
```
se não funcionar tente
```
npm i @gorhom/bottom-sheet@
```
agora suas dependências para animações e gestos
```
npx expo install react-native-reanimated react-native-gesture-handler
```

### Uma biblioteca que fornece uma API para lidar com gestos complexos.
documentação do gesture handler
> https://docs.expo.dev/versions/latest/sdk/gesture-handler/
```
npx expo install react-native-gesture-handler
```

### Uma biblioteca que fornece um componente Mapa que usa o Google Maps no Android e o Apple Maps ou o Google Maps no iOS.
documentação do MapView
> https://docs.expo.dev/versions/latest/sdk/gesture-handler/
```
npx expo install react-native-maps
```

### Uma biblioteca que fornece acesso à leitura de informações de geolocalização, sondagem da localização atual ou assinatura de eventos de atualização de localização do dispositivo.
documentação do Expo Location
> https://docs.expo.dev/versions/latest/sdk/location/
```
npx expo install expo-location
```

### Um componente React que renderiza uma visualização para a câmera frontal ou traseira do dispositivo.
documentação do Expo Camera
> https://docs.expo.dev/versions/latest/sdk/camera/
```
npx expo install expo-camera
```

### Certifique-se de que suas dependências estão corretas
#### Verifique se há outros pacotes desatualizados ou incompatíveis:
```
npm outdated
```

### Limpe o cache do Expo
#### Às vezes, problemas podem surgir devido a caches antigos. Limpe os caches com o comando:
```
npx expo start --clear
```
ou
```
npx expo --reset-cache
```
### Se persistir limpe o cache do Metro Bundler 
#### Cache residual pode causar travamentos. Execute os comandos abaixo para limpar:
```
npm cache clean --force
npx expo start --clear
```

# Backend
dentro do projeto tem uma pasta backend, dentro dela um zip api.zip
extraia a pasta .zip e rode o comando dentro da pasta api pois ele é feito em node:
```
npm i
```
e agora rode o comando para iniciar o servidor:
```
npm start
```
### OBS
voltando para o mobile dentro da pasta services no arquivo api.ts mude a URL de acordo com dv sua máquina

### Banco de dados
> https://www.prisma.io
para acessar entre na pasta api e rode o comando
```
npx prisma studio
```
