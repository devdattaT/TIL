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
