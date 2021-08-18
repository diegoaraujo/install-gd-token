# install-gd-token
Instructions to install GD Token in fedora 33

* Confirm your device model:

```bas
lsusb

outputs:
Bus 001 Device 007: ID 1059:0019 Giesecke & Devrient GmbH StarSign CUT S

```

* Download RPM package from:

https://certificaat.kpn.com/files/drivers/SafeSign/SafeSign%20IC%20Standard%20Linux%203.6.0.0-AET.000%20centos8%20x86_64.rpm

* Install package

```bash
sudo dnf install "SafeSign IC Standard Linux 3.6.0.0-AET.000 centos8 x86_64.rpm"
```

* Open Token Administration Utility and check version (Help menu)

![image](https://user-images.githubusercontent.com/301530/129969293-213004cb-53b3-4fad-b598-6b361ca7bb3f.png)
![image](https://user-images.githubusercontent.com/301530/129969454-229ce854-3962-46de-99c0-f9531c9b7d5a.png)

* Install SafeSign in firefox

![image](https://user-images.githubusercontent.com/301530/129970224-92d47708-8db6-49d3-b3ea-f261d97b7dc8.png)

