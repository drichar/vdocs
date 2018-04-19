Installation
---

::: tip PREREQUISITES
* [Docker for Mac](https://docs.docker.com/docker-mac/)
* [NodeJS](https://nodejs.org/en/download)
* git-crypt (`brew install git-crypt`)
* gulp (`npm install -g gulp-cli`)
* Add `development.pixwel.com` to your /etc/hosts file pointing to `127.0.0.1`
:::

::: warning LINUX PREREQUISITIES
* `sysctl -w vm.max_map_count=262144` (to set this value permanently, use `vm.max_map_count = 262144` in `/etc/sysctl.conf` for ElasticSearch)
:::

### Steps

``` bash
git clone git@github.com:Pixwel/platform.git
cd platform
git checkout 2.x
cp some/location/gitcrypt.key .
cd cli
sudo npm link
cd ..
pixwel path
pixwel install
pixwel up
```

Then let's add some data:

`cd utils; ./db-copy-prod-to-local.sh`

You should now be able to browse to [https://development.pixwel.com:8080](https://development.pixwel.com:8080) right away to start using the system.
You can also serve the UI through some live reloading feature by running `pixwel ui` or `pixwel ui --dev` instead. In this case the served UI will be [https://development.pixwel.com:8000](https://development.pixwel.com:8000).

Running tests
--

``` bash
pixwel kahlan
```
