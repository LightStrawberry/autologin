# AUTO SSH LOGIN
Auto SSH Login Tool

# Install

### install dependencies
```
apt-get install expect
```

### install tool
```
git clone https://github.com/LightStrawberry/autologin.git
sudo cp autologin/autologin /usr/local/bin/
```

### set config

write your server ssh config in ~/.autologinrc
```
server_name|server_ip|user|pass|port
```

# Usage

just run autologin with your server_name
```
autologin skywalker
```
