# Ansible Role: RMLAMP
=========

Remove my [rol](https://galaxy.ansible.com/fvarovillodres/lamp/) of LAMP stack on Debian/Ubuntu

## Instalation
h

$ ansible-galaxy install fvarovillodres.rmlamp

## Requirements

No special requirements; note that this role requires root access, so either run it in a playbook with a global `become: yes`, or invoke the role in your playbook like:

    - hosts: database
      roles:
        - role: fvarovillodres.rmlamp
          become: yes


## Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - fvarovillodres.rmlamp

## Author Information
------------------

Francisco M Varo Villodres student of SysAdmin in Málaga, Spain.
