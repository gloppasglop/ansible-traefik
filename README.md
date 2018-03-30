Traefik
=======

Install traefik on my lab server.

Trafik binary is downloaded from githu traefik repo: https://github.com/containous/traefik/releases

Requirements
------------

None

Role Variables
--------------

traefik_install_dir: /usr/local/bin
traefik_version: v1.5.4
traefik_checksum: sha256:8f7b2d3d7e893d2bc9310ecda2b8654c3a2b2b5e267b3bdf3f36b55ba21b5813

traefik_status_port: ":8080"
traefik_acme_email: gloppasglop@gmail.com
traefik_docker_domain: gloppasglop.com

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: traefik
           traefik_version: v1.5.4
           traefik_checksum: sha256:8f7b2d3d7e893d2bc9310ecda2b8654c3a2b2b5e267b3bdf3f36b55ba21b5813

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
