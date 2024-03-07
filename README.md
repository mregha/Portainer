## Cara Install Portainer Web Ui Monitoring Docker
1. docker pull portainer/portainer
2. mkdir /opt/portainer /data
3. docker run -d -p 9000:9000 --restart always -v /var/run/docker.sock:/var/run/docker.sock -v /opt/portainer:/data portainer/portainer
4. Login Docker Portainer :
	http:// IP(Ip local device):9000
	Buat User dan Password
