# Canina Growshop

Dev envirement

docker run -d \
    -p 21:21 \
    -p 21000-21010:21000-21010 \
    -e USERS="one|Passw0rd!" \
    -e ADDRESS=ftp.site.domain \
    delfer/alpine-ftp-server
