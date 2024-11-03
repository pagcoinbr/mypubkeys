# mypubkeys

```bash
mkdir ~/.ssh
```

```bash
sudo rm -rf ~/ssh/authorized_keys
```

```bash
cp ssh ~/.ssh/mypubkeys/authorized_keys ~/ssh/authorized_keys
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



