## **What problem you experience:**

This and that don't work 

## **What error messages you get:**

When i do this i get this message

## **What steps did you make and what was the outcome:**
* 1... -> Nothing changed
* 2... -> Solved partialy
* 3... -> Something

# My setup is as follows:

## Docker Templates:
**Right Click Docker -> Click 🔧 `Edit`**
### Name
![name.jpg](/name.jpg)

Nextcloud docker name: 
Database docker name:
Redis docker name:
Swag docker name:

### Repository
![repository.jpg](/repository.jpg)

Nextcloud docker repository: 
Database docker repository:
Redis docker repository:
Swag docker repository:
## Network
![network_type.jpg](/network_type.jpg)

Nextcloud docker network type: 
Database docker network type:
Redis docker network type:
Swag docker network type:

Use unraid's terminal and run `docker network ls`
Output: ```Output here```

# Logs
**Right Click Docker -> Click 📝`Logs`**
## Docker Logs

Nextcloud docker log ->
```
Insert nextcloud docker log here
```

Database docker log ->
```
Insert database docker log here
```

Redis docker log ->
```
Insert redis docker log here
```

Swag docker log ->
```
Insert swag docker log here
```

## App Logs

### Nextcloud
Go to the directory you mapped nextcloud's `/data` directory. (Usually `/mnt/user/nextcloud`)
Open `nextcloud.log` and copy/paste the contents here
```
Insert nextcloud.log content here
```
**Right Click Docker -> Click 💻`Console`**
* Run `occ status`
	Output: ```Output here```
*	Run `occ maintenance:mode`
	Output: ```Output here```

## App Configs

### Nextcloud

Go to the directory you mapped nextcloud's `/config` directory, (Usually `/mnt/user/appadata/nextcloud`)
Go from there to `www/nextcloud/config`
Open `config.php` and copy/paste the contents here
**FIRST OBFUSCATE ANY IDENTIFING INFO, like instanceid, passwords, secrets, domains, data-fingerprint**
```
Insert config.php content here
```


