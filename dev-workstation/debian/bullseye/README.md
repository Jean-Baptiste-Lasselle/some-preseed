
## How to geenrate the preseed file


```bash
sudo apt-get install -y debconf-utils

sudo debconf-get-selections --installer | tee dev-workstation/preseed.devops-workstation.cfg

```
