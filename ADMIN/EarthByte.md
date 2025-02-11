This file contains information from EarthByte team.

### How to build the website

- Use the [environment.yml](https://github.com/EarthByte/gsfml/blob/master/environment.yml) to create a conda env.
- Activate the conda env `conda activate python38` (the env name needs change.)
- Run “make release” in the root folder of the gsfml repository, and copy the files to the web server.

### EarthByte server

- ip:          104.128.67.157
- domain name: earthbyte.org
- path:        /var/www/gsfml
- Apache conf: /etc/apache2/sites-enabled/gsfml-ssl.conf /etc/apache2/sites-enabled/gsfml.conf
- login:       ask Michael Chin for technical support. Prepare and send a public key to MC.

### How to upload files

- build the website if needed
- see the "EarthByte server" section for server IP and file path
- use [Cyberduck](https://cyberduck.io/)
- ask Michael Chin to create an account for you

### SSL certificate

- renew certificate `sudo certbot renew`

Note: 
We cannot make the gsfml image. The gsfml_map.sh does not work anymore. Missing curv.24.1.img??? 
Using the old GSFML_map_small.jpeg and GSFML_map.pdf. I have curv_32.1.nc at https://repo.gplates.org/webdav/mchin/data/VGG/.
But I am not sure if curv_32.1.nc can work as a replacement of curv.24.1.img.
