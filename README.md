# Minio Object Store

## Run Minio

```script
docker-compose up
```

## Create account

- Go to ```http://localhost:9090``` and login with ```admin```/```password```.
- Click ```Identity``` --> ```Users``` and then click the ```Create User``` button.
- Fill in username and password and assign ```readwrite``` policy

## Run the minio_python.py script

- Change the username and password in the script
- Run the ```minio_python.py``` script

## Check results

- Go to ```http://localhost:9090``` and login with ```admin```/```password```.
- The bucket should appear in the list, browse the bucket to see its contents