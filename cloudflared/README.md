# apollo-us-hstgr/cloudflared

This is my config files for cloudflared container.

Rename .env.example to .env and update your cloudflare token inside of that file on your server.

You could also use update-cloudflared github action and automatically deploy the code to your server and update your token, you will need some github actions repository secrets to do this those being.

APOLLO = Ip of my server Apollo.
APOLLO_USER = User to SSH into that server.
APOLLO_PRIVATE_SSH_KEY = Private key to allow github action to connect with no SSH password.
DIRECTORY = This is the directory of where this Repository sits on my server.
CLOUDFLARE_TUNNEL_TOKEN = Your cloud flare tunnel token.

Make sure to still have a blank .env file inside the /cloudflared folder otherwise the github action will fail.
