# Netflix Application (movie streaming platform)
![](readmeAsset/register.gif)
## How long did it take ?
2 weeks

## challenge accepted ?
- [x] team project (coordination is key to success)
- [x] own local webserver using docker compatible with any os
- [x] no security breaks


## What did I learn ?
  * omniauth login
  * manage a movie torrent api
  * stream the movie while downloading the torrent on server
  * react.js
  * redux
  * node.js
  * bootstrap and templating
  * socket.io
  * implementing working UI fast with react
  * working very fast with deadlines
  * working with team mates


## What is this project ?
This is a movie streaming app that has 3 main features :

### 1. User Features
A user can register. A user can login with various method (facebook / google / 42network). A user can change his information and can upload personnal movies. Users can see other users page.

![](readmeAsset/profile.gif)

### 2. Gallery of Movie and Search Engine
The website interrogates yify API and will render by default the most highly rated movies it can find. We build a search engine that can render a query string such as "harry" or "harry potter", specified genra ("horror", "adventure", "drama"...), specified years or popularity/ratings. You can then sort it by ascending or descending order.
![](readmeAsset/search.gif)

### 3. Streaming
you can click on the movie to go to its details page. The streaming link automatically activates from backend and you can directly stream it on your browser while it's downloading in back.
![](readmeAsset/film.gif)

For more information about the project please see the pdf subject available in french and english at ![subject](https://github.com/nepriel/netflix-42/tree/master/subjects "subject").

### How do I run it on my laptop ?
Edit your `/etc/hosts` file:

```
127.0.0.1   si.hpt.local
127.0.0.1   app.hpt.local
127.0.0.1   mongo.hptdb.local
```

Navigate to frontend

```bash
cd frontend
```

Copy the env variables for developement environment

```bash
cp .env-template .env
```

Navigate to backend

```bash
cd backend
```

Copy the env variables for developement environment

```bash
cp .env-template .env
```

Within the backend path creat a new foldder (if it does not exist)

```bash
mkdir uploads
```

Build the project from the root directory
```bash
docker-compose up --build
```

Within the backend path creat a new foldder (if it does not exist)

```bash
mkdir uploads
```

et voilà ! go to `http://localhost:5000`

![alt text](https://github.com/nepriel/netflix-42/blob/master/readmeAsset/correction.PNG "result of evaluation of project")
