# Usage

## Setup
```bash
$ git clone <repo>
$ cd <project>
$ npm install # or yarn or pnpm
```

## Environment
```bash
$ cp .env.example .env # and fill in the values
```

## Database
```bash
$ docker-compose up -d
```


## Run
```bash
$ npx prisma db push # or npx prisma migrate dev
$ npx prisma db seed
```


