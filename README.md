# Odoo with docker
* default master pasword : `rizkidesu@2022`
* link : `localhost:8069`
* managae database : `localhost:8069/web/database/manager`

## 1 Usage

### a CLoning repo

``` bash
git clone https://github.com/RizkiDesu/odoo_docker.git
```

### b Biar bisa akses folder dengan bebas(linux)

- **If you get any permission issues**, change the folder permission to make sure that the container is able to access the directory:

``` sh
sudo chmod -R 777 addons
sudo chmod -R 777 etc
sudo chmod -R 777 postgresql
```

### c Start the container:
``` sh
docker-compose up
```

Then open `localhost:8069` to access Odoo 16.0.


## 2 SCAFFOLDING Odoo

``` sh
docker exec -it <nama_kontainer> /usr/bin/odoo scaffold <nama-modul> /mnt/extra-addons
```


## 3 Odoo container management

**Run Odoo**:

``` bash
docker-compose up -d
```

**Restart Odoo**:

``` bash
docker-compose restart
```

**Stop Odoo**:

``` bash
docker-compose down
```
## 4 [tutorial odoo 16](tutor.md)

## 5 docker-compose.yml

* odoo:16.0
* postgres:15


## 6 refrensi 
- [odoo mates](https://youtube.com/playlist?list=PLqRRLx0cl0hoZM788LH5M8q7KhiXPyuVU&si=MhywVwnZhOpRHCj4)
- [auto didak](https://youtube.com/playlist?list=PLxnh_lDN7wxenhhZYqYQcB4JRMHtRs-cP&si=LVSFPzDKL2FZ5KWy)
- [ppt](https://drive.google.com/drive/folders/1ADuw4iBJnekfeKB8NNP2LuWCQMSAUt2w)
- [modif_code_form](https://github.com/minhng92)


## 7 screenshots.


<img src="screenshots/posgree.png" width="50%">

<img src="screenshots/home.png" width="100%">