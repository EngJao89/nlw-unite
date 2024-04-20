## 💻 NLW UNITE

Projeto desenvolvido na NLW UNITE que conta com Frontend em ReactJS, mobile em React Native e backend em NodeJS. É um sistema completo de gerenciamento de eventos.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Veja **[clone](https://github.com/EngJao89/nlw-unite.git)** para saber como clonar o repositório para sua máquina.

### 🔧 Instalação

Para rodar o projeto após clonar na sua máquina. Será necessário seguir as etapas a seguir.

Comece com mobile e usando seu empacotador padrão rode:

```
npm install
```

Ou utilize:

```
yarn install
```

Para utilizar o web e usando seu empacotador padrão rode:

```
npm install
```

Ou utilize:

```
yarn install
```

Para utilizar a api usando seu empacotador padrão rode:

```
npm install
```

Ou utilize:

```
yarn install
```

Após instalar as dependencias suba o container do docker com PostgreSQL rode:

```
docker compose up
```

Após subir o container do docker, faça as migrações do banco rode:

```
npx prisma migrate dev
```

Ao terminar siga a proxima etapa para rodar o projeto:

Para rodar o projeto mobile:

```
npx expo start
```

Ou utilize:

```
yarn start
```

Para rodar o projeto web:

```
npm run dev
```

Ou utilize:

```
yarn start
```

Para rodar o projeto api:

```
npm run dev
```