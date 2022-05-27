#### Tab 1 (backend) port 9000
```npm install -g @medusajs/medusa-cli```
```docker-compose up -d```
```cd backend```
```npm install```
```npm run seed```
```medusa develop```

#### Tab 2 (admin) port 7000 + graphql http://localhost:7000/___graphql
``` brew install yarn ```
```npm install -g gatsby-cli```
```cd adminfront```
```yarn install``` (npm install is broken for adminfront)
```gatsby develop -p 7000```

#### Tab 3 (storefront) port 8000
```cd storefront```
```npm install```
```gatsby develop -p 8000```
