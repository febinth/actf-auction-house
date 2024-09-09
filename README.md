# actf-auction-house

1.	Install Docker - https://docs.docker.com/get-started/get-docker/ 
2.	Clone the repository - https://github.com/febinth/actf-auction-house.git 
3.	On the terminal, navigate to the repository root and run the below command.
```sh
docker-compose up -d
```
The entire system should be up and running and can be verified from the Docker Desktop app or by running the below command on the terminal.
```sh
docker ps
```
4.	To access the auction webpage, go to http://localhost:8080/ 
5.	To create products and auctions, go to http://localhost:8080/admin/. Enter the username – “admin”, password – “admin”.