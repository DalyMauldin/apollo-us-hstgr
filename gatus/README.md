# apollo-us-hstgr/gatus

These are my configs for Gatus on my Apollo server, using an sqlite DB.

I use github actions to deploy my code to my server so there is a few github actions reposiory secrets I use, those being.

APOLLO = Ip of my server Apollo.
APOLLO_USER = User to SSH into that server.
APOLLO_PRIVATE_SSH_KEY = Private key to allow github action to connect with no SSH password.
DIRECTORY = This is the directory of where this Repository sits on my server.

Use .env.example as the base of your config, I have my server ips and domains inside enviornment variables to be able to keep this code on Github. Rename .env.example to .env and update the variables to match your enviornment and update the /config/config.yml to match the same enviornment variables and remove or add services listed in the config.
