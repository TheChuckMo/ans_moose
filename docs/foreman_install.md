Foreman Install
===============

foreman-installer --secanrio katello \
--disable-system-checks \
--foreman-initial-organization "moosejudge" \
--foreman-initial-location "home" \
--certs-server-cert "/etc/pki/tls/certs/foreman_foreman.home.moosejudge.com_crt.pem" \
--certs-server-cert-req "/etc/pki/tls/certs/foreman_foreman.home.moosejudge.com_ca.pem" \
--certs-server-key "/etc/pki/tls/private/foreman_foreman.home.moosejudge.com_key.pem" \
--certs-server-ca-cert "/etc/pki/ca-trust/extracted/pem/tls-ca-bundle.pem" \
--enable-foreman-compute-gce \
--enable-foreman-compute-libvirt \
--enable-foreman-plugin-bootdisk \
--foreman-ipa-authentication \
--enable-foreman-plugin-ansible 
