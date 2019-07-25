# GCP-instance-create

pip install apache-libcloud


1. Create serviceaccount credentials (JSON format): https://console.cloud.google.com/apis/credentials
2. Create new project Compute App: example web-1 (ID: web1-215116)
3. run ansible playbook: ansible-playbook /etc/ansible/roles/gcp/tasks/ansible-gcp.yml

more example and full docs: https://docs.ansible.com/ansible/devel/modules/list_of_cloud_modules.html#google
