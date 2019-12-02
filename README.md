# ansible_playbook_docker_installation
This ansible playbook installs docker, by setting up the repository and installing the docker engine (community).
Also, it does the following:

- Restart the docker service only if the docker engine package gets updates
- Add ubuntu user to the docker group as in: sudo usermod -aG docker your-user
