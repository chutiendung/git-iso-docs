# git-iso-docs
A Git server as a document management system for ISO9001

## Features

A Vagrant box ready for use featuring:
  - Locally hosted with full encryption (git-remote-gcrypt)
  - GitLab front-end for document management
  - Searchable, pretty wiki-style document viewer from Hugo
  - Regularly scheduled document reviews
  - Customizable rights groups
  - Email alerts
  - Mobile friendly


### Instructions





### Detailed setup information

#### **Vagrant**

```
vagrant init ubuntu/precise32
```
```
vagrant up
```

####**GitLab**

From https://about.gitlab.com/downloads/#ubuntu1204:

```
sudo apt-get install curl openssh-server ca-certificates postfix
```
```
curl -sS https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash
```
```
sudo apt-get install gitlab-ce
```
```
sudo gitlab-ctl reconfigure
```
