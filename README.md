# facebak-api

##### Clone the repository

```
git clone https://github.com/YumeT023/facebak-api
```

##### Install the dependencies

navigate to the project directory: `cd facebak-api`

```
<<<<<<< HEAD
yarn install or npm install
=======
npm install
>>>>>>> 7090b1e0a456f3458b29ca8ac31f1c24a3518bdc
```

##### Sync your db with the Prisma migration

##### # update the .env according to your credentials

```
<<<<<<< HEAD
DATABASE_URL="postgresql://postgres:{{name}}@localhost:5432/{{database}}?schema=public"
```

- `{{name}}` your postgreSql username, _postgres_ by default on windows
- `{{database}}` name of your db 
=======
DATABASE_URL="postgresql://{{name}}:{{password}}@localhost:5432/{{database}}?schema=public"
```

- `{{name}}` your postgres username, _postgres_ by default on windows
- `{{password}}` your postgres password
- `{{database}}` db name
>>>>>>> 7090b1e0a456f3458b29ca8ac31f1c24a3518bdc

##### # Push the prisma state to the provided database

```
npx prisma db push
```

<<<<<<< HEAD
=======
#### Insert mock data into the db (OPTIONAL: if you want to have some data)

```
npx prisma db seed
```

>>>>>>> 7090b1e0a456f3458b29ca8ac31f1c24a3518bdc
#### Run the dev server

```
npm run dev
```

#### Build & run the build

```
npm run build
node  build/app.js
```

#### Miscellaneous

- `Format` npm run format
- `lint` check code style issues
