# nextcloud-docker

Security test: https://scan.nextcloud.com/

Static IPs:
nextcloudweb: 172.19.0.23:81
nextcloudoffice: 172.19.0.22:9980

test nextcloudoffice:
curl -k http://172.19.0.22:9980

SSL: If it fails, you have to debug SSL settings.
curl -v https://office.paczos.org:9980/hosting/discovery
