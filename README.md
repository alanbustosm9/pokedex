<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run on dev

1. Clon repository
2. Run

```
yarn install
```

3. Need to have Nest CLI installed

```
npm i -g @nestjs/cli
```

4. Run DB

```
docker-compose up -d
```

5. Clone file **.env.example** and change name to **.env**

6. Fill environment values con file

7. Run app in dev

```
yarn start:dev
```

8. Rebuild seed DB

```
http://localhost:3000/api/v2/seed
```

## Stack

- Nest
- MongoDB
