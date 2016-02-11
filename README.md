# LampstackMinimal
ansible-playbook -i ../inventory.ini bootstrapSite.yml 

# https call
curl -k https://lb:443

#https call with client certificate
curl -k https://lb:444 --key roles/lb/files/myclientname.key --cert roles/lb/files/myclientname.crt
