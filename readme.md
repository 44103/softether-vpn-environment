# SoftEther VPN Environmnt
This repository is SoftEther VPN Environment by Docker.

## Installation Procedure
1. Clone this repository
   ```sh
   git clone ...
   ```
1. Start container
   ```sh
   docker-compose up -d
   ```
1. Edit VPN Server Config
   - Install [SoftEther VPN Server Manager](https://www.softether.org/)  
   or
   - Enter docker container and Type vpncmd
     ```sh
     docker-compose exec app bash
     ./vpncmd
     ```

## Execution Check Environment
|                | Values              |
| :------------- | :------------------ |
| Synology       | DS218+              |
| CPU            | INTEL Celeron J3355 |
| Docker         | 20.10.3             |
| docker-compose | 1.28.5              |
