# A basic template of NestJs + Prisma

This is a basic NestJS project that uses Prisma as an ORM. It implements basic authentication with JWT and role-based authorization.

## Usage

### Setup
```bash
$ git clone <repo>
$ cd <project>
$ npm install # or yarn or pnpm
```

### Environment
```bash
$ cp .env.template .env # and fill in the values
```

### Database
```bash
$ docker-compose up -d
```


### Run

```bash
$ npx prisma migrate dev # to run the migrations
```
Or
```bash
$ npx prisma db push 
$ npx prisma db seed
```


