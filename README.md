# A hackernews clone built using React, Apollo + GraphQL

I am building this project as part of the How To GraphQL tutorial [React & Apollo Tutorial](https://www.howtographql.com/react-apollo/0-introduction/)

## How to use it

### 1. Clone repo

```sh
git clone https://github.com/maffsojah/hackernews-clone/
```

### 2. Install dependencies

```sh
cd hackernews-clone
yarn install
```

### 3. Install dependencies & Deploy the Prisma database API

To install the Prisma CLI globally with Yarn, use the following command:

```sh
yarn global add prisma
```

Also, run the following commands:

```sh
cd react-apollo/server
yarn install
prisma deploy
```

Then, follow these steps in the interactive CLI wizard:

1. Select **Demo server**
1. **Authenticate** with Prisma Cloud in your browser (if necessary)
1. Back in your terminal, **confirm all suggested values**

### 4. Start the server

To start the server, all you need to do is execute the `start` script by running the following command inside the `server` directory:

```sh
yarn start
```

> **Note**: If you want to interact with the GraphQL API of the server, you can navigate to [http://localhost:4000](http://localhost:4000).

### 5. Run the app

```sh
yarn start
```

You can now open your browser and use the app on [http://localhost:3000](http://localhost:3000)
