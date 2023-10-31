# Salvum_Prebuilt_Native

This is the package deployed for Appalachian State University to support interactive cybersecurity education.

Native Ubuntu 20 LTS installer. For cross-platform Salvum, see containerized

To run execute these commands after you've got your Docker running with Desktop or what not:
```
docker load < slm_community_docker.tar
docker run -it qvlx_salvum-20.04:community
```

In order to get host networking capability and see other devices just like the 
host would, use the following command:
```
docker run --network host -it qvlx_salvum-20.04:community
```
To mount a host directory through the container, use this command:
```
docker run -it -v <host_dir>:/home/usr qvlx_salvum-20.04:community
```
Note: host_dir is the full path to a host directory that the user wishes to mount.

The mount makes host files available to the container, in the usr directory. Files 
can easily be moved in and out of the Salvum environment and operated upon.
Arguments can be combined to employ all the mentioned features like so:
```
docker run –-network host -it -v <host_dir>:/home/usr qvlx_salvum...
```

$t@$h here: I recommend containerized then if you want code contact me; it's alot of file exchange

Servf, Yara, and PXE functionality taken out of this along with the QVLx FCC db.

This made the image way smaller and easier to work with. Servf should also not work as its been commented.

In conclusion, this installable package is smaller than the full 300+ app version by design.

$t@$h r00r00 n3wm4n m0nZSt3r Matzr3lla 0mg33 k!r!t0
