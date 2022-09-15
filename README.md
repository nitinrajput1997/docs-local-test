# docs-local-test

### Run locally
Under docs folder run
```bash
docker-compose up
```

When we want to do some changes
```bash
sudo rm -rf build
docker-compose up
```
**Note:** Then in next tty cd to /build/_build/html .And run this command
```bash
python3 -m http.server 80 (worked)
```
Visit localhost:80. 
when changes is done and docker-compose rebuild files
```bash	
ctrl+c 
cd and then cd -
python3 -m http.server 80
```
