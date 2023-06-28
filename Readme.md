# Steps to install node on ubuntu
## Update System Packages
sudo yum update

##  Install Development Tools
sudo yum groupinstall "Development Tools"

##  Install Node.js using NodeSource repository:
curl -sL https://rpm.nodesource.com/setup_14.x | sudo bash -
sudo yum install -y nodejs

## Verify the Node.js installation:
node -v
npm -v


# SOnar for node
```bash
npm run sonar
# If issues do following
npm cache clean --force
```
