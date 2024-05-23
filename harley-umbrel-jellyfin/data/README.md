# Readme for Jellyfin Data Directory
In the docker-compose.yml, I mounted additional volumes:
- movies
- tv_shows
- music
- books

I usually replace them with a symbolic link:
```bash
$ ln -s {path_to_movies} movies
```