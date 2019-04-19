# uclalib_role_docker-ce

This role is designed to install Docker Community Edition on CentOS 7 and RHEL 7 Servers

### Using this role
You can include the role as you would normally any other. The only special variable to define is if you want to install composer. If you want to install Docker Community Edition, run the following command:

    ansible-playbook -l localhost playbooks/test_install.yml -vv

If you want to install docker-composer along with Docker, run the following:

    ansible-playbook -l localhost -e "docker_compose_install=true" playbooks/test_install.yml -vv

### Contact

If you have any questions or have a recommendation to suggest, feel free to open a ticket in this project's [issues queue](https://github.com/UCLALibrary/uclalib_role_docker-ce) or contact me at <a href="mailto:lightningcount513@gmail.com">Anthony Vuong</a>.