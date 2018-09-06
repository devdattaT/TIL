# TILs for Sept 2018

---

## 2018-09-06

- How to install Postgresql client 10 on Ubuntu [(Gist)](https://gist.github.com/emattson/ffbceee5952c4a0de441bd96b952821c):

  //taken from https://www.postgresql.org/download/linux/debian/

  //assumes you are root

  echo 'deb http://apt.postgresql.org/pub/repos/apt/ stretch-pgdg main' > /etc/apt/sources.list.d/pgdg.list

  wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | apt-key add -

  apt-get update

  yes Y | apt-get install postgresql-client-10

- How to Create Key:
  ssh-keygen -t rsa -b 4096 -C "email@example.com"

- How to install php7.1 on Ubuntu Server:

  From [Link](https://ayesh.me/Ubuntu-PHP-7.1)

  - Add PPA:

    `sudo add-apt-repository ppa:ondrej/php`

  - Update apt

    `sudo apt update`

  - Install PHP core:

    `sudo apt-get install php7.1 php7.1-common`

  - Install others:

    `sudo apt-get install php7.1-curl php7.1-xml php7.1-zip php7.1-mbstring`
