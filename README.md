# About
Project Template for Salt Masters /srv.

# Usage
## Add this repo as Git Submodule to a project

```
git submodule add --name .salt-project-template -b master -- https://github.com/sysadmws/salt-project-template .salt-project-template
```

## Run install.sh
```
cd .salt-project-template
TELEGRAM_TOKEN=xxx \
	TELEGRAM_CHAT_ID=xxx \
	ROOT_EMAIL=xxx \
	SALT_MINION_VERSION=xxx \
	SALT_MASTER_1_NAME=xxx \
	SALT_MASTER_1_IP=xxx \
	SALT_MASTER_1_EXT_IP=xxx \
	SALT_MASTER_1_SSH_PUB=xxx \
	SALT_MASTER_2_NAME=xxx \
	SALT_MASTER_2_IP=xxx \
	SALT_MASTER_2_EXT_IP=xxx \
	SALT_MASTER_2_SSH_PUB=xxx \
	SALT_MASTER_PORT_1=xxx \
	SALT_MASTER_PORT_2=xxx \
	STAGING_SALT_MASTER=xxx \
	CLIENT=xxx \
	DEFAULT_TZ=xxx \
	./install.sh ../some/salt/repo/path
```
