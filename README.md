# Salvum_Prebuilt_Native

This is the package deployed for Appalachian State University to support interactive cybersecurity education.

Native Ubuntu 20 LTS installer. For cross-platform Salvum, see containerized

Run this command to get started:
```
sudo ./install_salvum.sh
```

This will then unpack the tarball into an slm directory. Once finished, cd into the slm directory and run:
```
sudo ./salvum
```

Note: You don't have to run as superuser but keep in mind most apps won't function properly.

Servf, Yara, and PXE functionality taken out of this along with the QVLx FCC db.

This made the image way smaller and easier to work with. Servf should also not work as its been commented.

In conclusion, this installable package is smaller than the full 300+ app version by design.

$t@$h r00r00 n3wm4n m0nZSt3r Matzr3lla 0mg33 k!r!t0
