USAGE

	bash doCerts <CA_SUBJECT> <CERT_FOLDER> <IP_LIST_SEPARATED_BY_COMMAS> <DNS_SEPARATED_BY_COMMAS> <EXPIRY_DATE>

**CA_SUBJECT -> the name of the ca**

**CERT_FOLDER -> Folder where the certificates will be generated**
		
	client/
		-rw-r--r-- 1 root  root  1679 jun 19 11:13 ca-key.pem
        -rw-r--r-- 1 root  root   973 jun 19 11:13 ca.pem
        -rw-r--r-- 1 root  root    17 jun 19 11:27 ca.srl
        -rw-r--r-- 1 root  root  1062 jun 19 11:27 cert.pem
        -rw-r--r-- 1 root  root  1050 jun 19 11:27 key.csr
        -rw-r--r-- 1 root  root  1679 jun 19 11:27 key.pem
        -rw-r--r-- 1 root  root   339 jun 19 11:27 openssl.cnf
        -rw-r--r-- 1 root  root  3867 jun 19 11:27 secret.yaml
	server/
		-rw-r--r-- 1 sergi sergi  973 jun 19 11:27 ca.pem
    	-rw-r--r-- 1 root  root  1123 jun 19 11:27 cert.pem
    	-rw-r--r-- 1 root  root  1675 jun 19 11:27 key.pem
    	
**IP_LIST -> List of Ip Addresses that the cert will certificate, ex: 127.0.0.1,127.0.10.10**

**DNS_SEPARATED_BY_COMMAS -> List of DNS names that the cert will certificate ex: dns1.local,dns2.local**

**EXPIRY_DATE -> days until de cert will expire, f.e: 365 (one year)**

