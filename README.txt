ansible-playbook playbook.yml --limit $(echo server-{47..50} | tr ' ' ',')
