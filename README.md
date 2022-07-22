# PPTP Docker-Compose-VPN
Run your own  vpn on your vps or server just in 2 seconds using docker and docker-compse
I prefer to buy a vps (1G RAM) from OVH and set up an ubuntu 20.04 or centos7

## Step 1
You have to Install Docker and Docker-Compose:
https://docs.docker.com/engine/install

## Step 2
change `.env.list ` file for your username and password ( you can change using vi or nano editor ) :

` PPTP_USER_LIST="username1 * password1 * \n username2 * password2 *" `

## Step 3

In project directory use this commond to run it:
` docker compose up `
and if you want to stop use ` docker compose down `


