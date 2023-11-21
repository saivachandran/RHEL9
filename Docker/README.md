# docker installation on rhel 9

**Step 1**: **Update the System**
```
sudo dnf update
```
**Step 2**: **Add Docker Repository to YUM**

```
sudo dnf config-manager --add-repo=https://download.docker.com/linux/centos/docker-ce.repo
```

**Step 3**: **Install Docker**

```
sudo dnf install -y docker-ce docker-ce-cli containerd.io
```

**Step 4**: **Start and Enable Docker**
```
sudo systemctl start docker
sudo systemctl enable docker
```
**Step 5**: **Verify Docker Installation**

```
docker --version
```





