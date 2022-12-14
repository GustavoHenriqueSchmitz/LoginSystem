# Login System

Aplicação desenvolvida usando: [NodeJS](https://nodejs.org), [NestJS](https://github.com/nestjs/nest), [Prisma](https://www.prisma.io).

## Clone do projeto

```
git clone https://github.com/GustavoHenriqueSchmitz/LoginSystem.git
```
## Instalação

### 1 - Instale NodeJS V16.17.0

**1.** Primeiro verifique se você já tem o node instalado executando os seguintes comandos:

```
node -v
npm -v
```

Se o resultado for algo como:
```
v16.17.0
8.15.0
```

Você pode pular esta etapa de instalação.

**2.** Abra um terminal e execute os comandos seguintes:
```
sudo apt-get install curl
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

**3.**
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

**4.** Feche o terminal atual e abra um novo, e prossiga executando o comando seguinte:
```
nvm install v16.17.0
```
### 2 - Instale docker-compose:

**1.** Primeiro verifique se você já tem o docker instalado, execute:
```
docker-compose -v
```
Se a versão for retornada com sucesso, pode pular esta etapa.

**2.** Execute os seguintes comandos:
```
sudo apt-get update            
sudo apt install docker-compose
```

### 3 - Instalar depêndencias:

**1.** Navegue até a pasta raiz do projeto, e execute:

```
npm install
```

### 4 - Inicializar o Prisma:

**1.** Navegue até a pasta /src.

**2.** Execute o comando:
```
npx prisma generate
```

## Executando a aplicação

**1.** Abra um terminal, e na pasta raiz do projeto, execute: 
```
sudo docker-compose up
```

**2.** Logo em seguida abra outro terminal, e ainda na pasta raiz do projeto. Execute um dos comandos </br>a seguir de acordo com o modo desejado:

```
# development
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
``` 
