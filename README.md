# GlusterFS-with-Ansible
## Architecture

> Our cluster is consists of 3 nodes, each having a 10G disk attached (/dev/sdb)
> and we have a client machine where we run our ansible playbook to install and configure glusterfs on our cluster

![architecture](/images/architecture.jpg)

## Project Files

**./create_lvm_partition.yml:**   playbook for creating a lvm partition

**./install_configure_glusterfs.yaml:** playbook for installing and configuring a GlusterFS cluster

**./nfs_setup.yml:** Playbook for setting up a NFS Server

## Author

**Youssef EL ASERY**

- [Profile](https://github.com/ysfesr "Youssef ELASERY")
- [Linkedin](https://www.linkedin.com/in/youssef-elasery/ "Welcome")
- [Kaggle](https://www.kaggle.com/youssefelasery "Welcome")


## 🤝 Support

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!