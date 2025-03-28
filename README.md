- nano ca/root-ca/root-ca.conf
- nano ca/sub-ca/sub-ca.conf
- cp -r ca/root-ca/certs ca/root-ca/certs_backup
- rm certs/ca.crt
- rm csr/sub-ca.csr
- cp /root/ca/root-ca/certs/ca.crt /home/nisha/certificate
- cp /root/ca/sub-ca/certs/sub-ca.crt /home/nisha/certificate/
- cp /root/ca/server/certs/server.crt /home/nisha/certificate/
- cp /root/ca/server/private/server.key /home/nisha/certificate/ 


