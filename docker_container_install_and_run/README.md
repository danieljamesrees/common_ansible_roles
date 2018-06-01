Role Name
=========

Installs and runs a simple service using a Docker container.

Requirements
------------

Requires Docker installed on the target system.

Role Variables
--------------

See defaults/main.yml.

docker_container_image_name: 'AVALUEMUSTBESET' # The name to pull from Docker Hub.
docker_container_name: 'AVALUEMUSTBESET' # The name to reference the container.
docker_container_port: AVALUEMUSTBESET # The port on which to start the main service.
docker_container_path: 'AVALUEMUSTBESET' # The path where the service will be installed on the container.
docker_container_tag: '' # The tag of the image on Docker Hub.
docker_container_url: '' # An URL at which the service can be accessed.
docker_container_version: 'AVALUEMUSTBESET' # The version of the image.

Dependencies
------------

None.

Example Playbook
----------------

See tests/main.yml.

License
-------

BSD.

Author Information
------------------

bringit.com.
