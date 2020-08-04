



sudo useradd -d /home/powerdg/ -s $(which bash) powerdg



sudo passwd powerdg



![image-20200128135742746](phone.assets/image-20200128135742746.png)

---



sudo sed -i '/PermitRootLogin/d' /etc/ssh/sshd_config

sudo bash -c "echo 'PermitRootLogin no' >> /etc/ssh/sshd_config"

sudo systemctl restart sshd



sudo sed -i '/PermitEmptyPasswords/d' /etc/ssh/sshd_config

sudo bash -c "echo 'PermitEmptyPasswords no' >> /etc/ssh/sshd_config"

sudo systemctl restart sshd

![image-20200128135714012](phone.assets/image-20200128135714012.png)



