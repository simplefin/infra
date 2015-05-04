Infrastructure for SimpleFIN services.

To test with docker:

    docker run --rm -v $(pwd):/code -it ubuntu /bin/bash
    cd /code
    local/install-ansible.sh
    ansible-playbook -i local/inventory -c local site.yml
