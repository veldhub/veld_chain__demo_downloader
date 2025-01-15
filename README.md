# veld_chain__demo_downloader

This repo contains [chain velds](https://zenodo.org/records/13322913) encapsulating demos of 
https://github.com/veldhub/veld_code__downloader .

## requirements

- git
- docker compose (note: older docker compose versions require running `docker-compose` instead of 
  `docker compose`)

Clone this repo with all its submodules
```
git clone --recurse-submodules https://github.com/veldhub/veld_chain__demo_downloader.git
```

## how to reproduce

Open any veld yaml file for more information.

Execute a chain with 
```
docker compose -f <VELD_CHAIN>.yaml up
```

For example
```
docker compose -f veld_demo_04__single_download__designate_file_name__extract.yaml up
```

Or execute all valid chains at once with this multichain:
```
docker compose -f veld_demo_10__multichain_all_previous.yaml up
```

