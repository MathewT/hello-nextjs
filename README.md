# hello-nextjs
Udemy course, following along.

### Build

```bash
docker build -t mathewt/hello-nextjs .
```

### Run image

```bash
docker run -ti -v $HOME/.aws:/root/.aws -v $HOME/.ssh:/root/.ssh  -v "$(pwd)"/pages:/usr/src/app/pages -v "$(pwd)"/build:/usr/src/app/out -p 0.0.0.0:3000:3000
```

```bash
npm run build
```
```bash
npm run export
```
