# WorkVerge DevOps Assessment

## Application

Node.js + Express application with two endpoints:

### GET /

Returns:

```json
{
  "application": "WorkVerge DevOps Assessment",
  "status": "running"
}
```

### GET /health

Returns:

```json
{
  "status": "healthy"
}
```

## Run Locally

```bash
npm install
node app.js
```

## Docker

# WorkVerge DevOps Assessment

## Application

Node.js + Express application with two endpoints:

### GET /

Returns:

```json
{
  "application": "WorkVerge DevOps Assessment",
  "status": "running"
}
```

### GET /health

Returns:

```json
{
  "status": "healthy"
}
```

## Run Locally

```bash
npm install
node app.js
```

## Docker

# WorkVerge DevOps Assessment

## Application

Node.js + Express application with two endpoints:

### GET /

Returns:

```json
{
  "application": "WorkVerge DevOps Assessment",
  "status": "running"
}
```

### GET /health

Returns:

```json
{
  "status": "healthy"
}
```

## Run Locally

```bash
npm install
node app.js
```

## Docker

Build image:

```bash
docker build -t workverge-devops-assignment .
```

Run container:

```bash
docker run -p 3000:3000 workverge-devops-assignment
```

## GitHub Repository

https://github.com/harii31/workverge-devops-assignment

## GHCR Image

ghcr.io/harii31/workverge-devops-assignment:latest
