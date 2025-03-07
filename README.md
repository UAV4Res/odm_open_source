
## Requirements 
- **Docker** (required for Linux or Windows installations) [Docker Installation Guide](https://docs.docker.com/get-docker/) .
- **Python** (latest version 3) corresponding to your OS [Python install Guide](https://www.python.org/downloads)

## Run images processing
- Upzip the file ```datasets.zip```
- When you done above steps, you can run Command Prompt / Terminal as following:
```bash
# Windows
docker run -ti --rm -v "<datasets_path>":/datasets opendronemap/odm --project-path /datasets project --orthophoto-resolution 0.5 --fast-orthophoto

# Mac/Linux
docker run -ti --rm -v "<datasets_path>":/datasets opendronemap/odm --project-path /datasets project --orthophoto-resolution 0.5 --fast-orthophoto
```
- Here you substitute ```<datasets_path>``` with location of the ```datasets``` folder that you've just unzipped

## Reference
Open Drone Map: https://opendronemap.org/odm/ 
