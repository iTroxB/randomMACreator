# **Random MACreator**


![](/img/random1.png)

Script that creates random MAC addresses by assigning real octets in the OUI (Organizationally Unique Identier) and randomizing the octets of the UAA (Universally Administered Address).

Focused on creating real random addresses that are not detected by MAC anti-spoofing techniques.

## Use

* Download the repository to your system

```shell
sudo git -C /opt clone https://github.com/iTroxB/randomMACreator.git
```

* Install the requirements by running **requirements.sh**

```shell
sudo bash /opt/randomMACreator/requirements.sh
```

* To use the system-level tool as an executable from a relative path, it is recommended to create a symbolic link to the /usr/bin directory from your repository directory.

```shell
sudo chmod +x /opt/randomMACreator/randomMACreator.sh
sudo ln -s /opt/randomMACreator/randomMACreator.sh /usr/bin/randomMACreator
```

## Execute tool

- randomMACreator

![](/img/random2.png)

---
