# mypubkeys

```bash
mkdir ~/.ssh
```

```bash
git clone https://github.com/pagcoinbtc/mypubkeys.git
```


```bash
sudo rm -rf ~/ssh/authorized_keys
```

```bash
cp ~/.ssh/mypubkeys/authorized_keys ~/.ssh/authorized_keys
```

```bash
chmod 600 ~/.ssh/authorized_keys
```

```bash
chmod 700 ~/.ssh
```

```bash
nano /etc/ssh/sshd_config.d/50-cloud-init.conf
```

mudar para "no"



