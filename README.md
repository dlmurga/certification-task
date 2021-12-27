Added to ansible.cfg

[defaults]

host_key_checking = false

remote_user = ubuntu

ask_pass = false

private_key_file = /var/lib/jenkins/keys/terraform.pem


[privilege_escalation]

become=True

become_method=sudo

become_user=root

become_ask_pass=False
