# sensor-ds18b20


## Installing the software

[Add the WildlifeSytems APT repository to your system](https://wildlife.systems/apt-configuration.html)

Install sensor-ds18b20.

```
sudo apt update
sudo apt install sensor-ds18b20
```

## Reading using `sensor-control`

```
sudo sr ds18b20
```

## Hardware configuration

TODO

## Building the Debian package

From within the sensor-ds18b20 directory:

```
debuild -us -uc -b
```
