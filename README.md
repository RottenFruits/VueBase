# VueBase

- image build

`docker build -t vue_base .`

- create container 

`docker run -v "path":/usr/src/app -p 9050:9050 --name app -it -d vue_base`

- container log in

`docker exec -it app sh`

- project create

`vue create .`

- app build

`npm run build`

- app start

`npm run serve -- --port 9050 --host 0.0.0.0`