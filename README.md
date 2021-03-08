# Aquinix
Easy Server Installation for Linux Operating System

## Manual Installation
```
sudo apt-get install git
git clone https://github.com/Clondus/Aquinix
sudo mv Aquinix /etc/
```

## Automatic Installation & Run
```
nano install.sh
```
Write these lines into the file
```
sudo apt-get install git
git clone https://github.com/Clondus/Aquinix
sudo mv Aquinix /etc/
cd /etc/Aquinix/
sudo chmod +x start.sh
./start.sh
```
Then save the file.
```
chmod +x start.sh
./start.sh
```

## How to use
```
cd /etc/Aquinix/
sudo chmod +x start.sh
./start.sh
```

## How to update
```
sudo rm -rf /etc/Aquinix/
sudo apt-get install git
git clone https://github.com/Clondus/Aquinix
sudo mv Aquinix /etc/
```
