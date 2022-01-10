# Add File

## Create folder

tmp is for the backup
working is for the backuping file

```bash
mkdir tmp 
mkdir working
mkdir restores
```

## How i run it 

```bash
docker-compose up --build
```

## How i exec it

```bash
docker exec -it docker_bacula-dir_1 bconsole
```

## How restore

Run bconsole then 

```txt
restore all
select jobID: 136
mark *
done
```

