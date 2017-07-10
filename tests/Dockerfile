from fedora:25
run mkdir /src && dnf install -y ansible
copy test-playbook.yml /src/
workdir /src
cmd ["ansible-playbook", "test-playbook.yml"]
