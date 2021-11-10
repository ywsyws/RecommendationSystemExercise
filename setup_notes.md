


### Note for docker
## Bring up container
```docker compose up -d```
or
```docker compose up --build -d``` to force rebuild image

## Stop container
```docker compose down```

## Launch jupyter notebook
Go to navigator and type and plug in the port that you used to build the container, e.g., 3000 in this case
```http://localhost:3000```

### Note for makefile
```make git m="your message"```

### Note if accidently commited big files
**Important:** Combine the 2nd and the 3rd answers

https://stackoverflow.com/questions/19573031/cant-push-to-github-because-of-large-file-which-i-already-deleted



### Note for git lfs
To restore broken files after git lfs migrate
```git lfs checkout```