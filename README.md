# CLOSE TO YOU

###  Icons
```
npm install @tabler/icons-react-native
```

### Como os itens é em SVG para conseguir renderizar
```
npx expo install react-native-svg
```

### Biblioteca para consumir o Backend
```
npm i axios
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
para acessar entre na pasta api e rode o comando
```
npx prisma studio
```
1:00:01h
