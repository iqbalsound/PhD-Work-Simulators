Showing Error while excuting from Ethernet</br>
**Solution:**</br>
	Run Following Command after Cloning GIT Repo</br>
	export SIMULATOR_EXTERNAL_IP=<your.server.ip></br>
	Than Run</br>
	make docker_build_and_up</br>
</br>

</br>Showing Error While **Runing docker-compose up -d** Shoung VERION Error</br>
**Solution:**</br>
	Open docker-compose.yml</br>
	Change 3.7 to 3.3 under VERSION at top of File</br>

</br>
</br>
**Missing** Docker-Compose Issue </br>
Solution:</br>
	in ROOT Mode</br>
	curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose</br>
	chmod +x /usr/local/bin/docker-compose</br>
	Check Version of docker-compose</br>
	docker-compose --version</br>
	OUTPUT will be Like</br>
	docker-compose version 1.21.2, build a133471</br>
</br>		

</br>Used on **RockyLinux**:</br>
	Type:</br>
	cat /etc/os-release</br>
		NAME="Rocky Linux"</br>
		VERSION="9.1 (Blue Onyx)"</br>
		ID="rocky"</br>
		ID_LIKE="rhel centos fedora"</br>
		VERSION_ID="9.1"</br>
		PLATFORM_ID="platform:el9"</br>
		PRETTY_NAME="Rocky Linux 9.1 (Blue Onyx)"</br>
		ANSI_COLOR="0;32"</br>
		LOGO="fedora-logo-icon"</br>
		CPE_NAME="cpe:/o:rocky:rocky:9::baseos"</br>
		HOME_URL="https://rockylinux.org/"</br>
		BUG_REPORT_URL="https://bugs.rockylinux.org/"</br>
		ROCKY_SUPPORT_PRODUCT="Rocky-Linux-9"</br>
		ROCKY_SUPPORT_PRODUCT_VERSION="9.1"</br>
		REDHAT_SUPPORT_PRODUCT="Rocky Linux"</br>
		REDHAT_SUPPORT_PRODUCT_VERSION="9.1"</br>
